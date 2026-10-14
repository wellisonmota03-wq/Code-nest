CODENEST STUDIO — BUILD PELO CELULAR COM GITHUB ACTIONS

O projeto inclui um workflow em .github/workflows/android-build.yml.
Ele gera um APK de teste e um AAB de release. O AAB gerado por este workflow ainda é NÃO ASSINADO e não pode ser enviado diretamente à Play Store até ser assinado.

PASSOS:
1. No celular, entre em github.com e crie uma conta ou entre na sua.
2. Crie um repositório novo, por exemplo: codenest-android.
3. Extraia este ZIP e envie TODOS os arquivos e pastas que estão na raiz do projeto (incluindo .github, app, build.gradle e settings.gradle) para a raiz do repositório. Não envie a pasta duplicada CodeNest_Android_Project; use os arquivos da raiz deste ZIP.
4. No GitHub, abra a aba Actions e habilite workflows se aparecer o pedido.
5. Escolha “Build CodeNest Android” e toque em “Run workflow”. Também inicia automaticamente quando fizer push na branch main.
6. Quando terminar com sucesso, abra a execução e baixe “codenest-build-files” em Artifacts.

ONDE FICAM OS ARQUIVOS:
- APK de teste: app/build/outputs/apk/debug/
- AAB de release: app/build/outputs/bundle/release/

IMPORTANTE:
- O AAB precisa ser assinado para publicação na Google Play. Não compartilhe a chave privada de assinatura nem sua senha.
- Este projeto é um protótipo WebView. O terminal ainda não executa código de verdade e o assistente não está conectado a um serviço de IA.
- A publicação depende de conta Google Play Console, testes/requisitos da conta e políticas da loja.
