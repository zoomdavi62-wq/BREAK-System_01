# BREAK System — projeto Android com Capacitor

Este pacote prepara seu `index.html` para virar um aplicativo Android usando Capacitor.

## Gerar o APK pelo GitHub

1. Extraia este ZIP.
2. Crie um repositório no GitHub e envie **todos os arquivos e pastas** deste projeto.
3. Confirme que o branch principal se chama `main`.
4. Abra a aba **Actions** do repositório.
5. Se aparecer um aviso, permita a execução de GitHub Actions.
6. Abra o fluxo **Gerar APK Android** e toque em **Run workflow**. Um envio para `main` também inicia a geração.
7. Quando terminar, abra a execução concluída e baixe o artefato **BREAK-System-APK**.
8. Dentro do ZIP do artefato estará `app-debug.apk`.

## Instalar no Android

Transfira `app-debug.apk` para o celular e abra o arquivo para instalar. O Android poderá pedir autorização para instalar apps dessa origem. Instale somente o APK que você mesmo gerou a partir deste projeto.

## Observações

- Este é um APK **debug**, adequado para testes e instalação pessoal; não é uma versão assinada para publicação na Play Store.
- O appId configurado é `com.breaksystem.evolucao`.
- O site foi colocado em `www/index.html`; seus recursos e dados locais continuam no próprio aparelho.
- Antes de publicar na Play Store, será necessário gerar uma versão release e configurar uma chave de assinatura.
