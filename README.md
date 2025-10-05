# Lista de Compras Simples

Aplicativo Flutter que mantém uma lista de compras, permitindo adicionar itens, marcar como comprados, limpar a lista e ver estatísticas rápidas. Os dados ficam salvos localmente através de SharedPreferences.

## Pré-requisitos
- [Flutter](https://docs.flutter.dev/get-started/install) instalado e configurado
- Emulador ou dispositivo físico (Android/iOS) com modo desenvolvedor habilitado

## Como executar
1. Instale as dependências: `flutter pub get`
2. Conecte um emulador ou dispositivo, ou defina o alvo web/desktop desejado
3. Rode o aplicativo: `flutter run`

O comando acima compila o app e abre a interface interativa. Use `r` no terminal para hot reload durante o desenvolvimento.

## Estrutura rápida
- `lib/main.dart`: interface e lógica de persistência
- `pubspec.yaml`: dependências do projeto (inclui `shared_preferences`)

## Dicas
- Para limpar builds anteriores, use `flutter clean`
- No Android, feche o aplicativo normalmente para garantir que a persistência seja aplicada
