### Guia rápido para instalação dos programas necessários para uso de certificado digital no Ubuntu 18.04 (Linux)

Instruções:

1) Abra um terminal de comando e digite o seguinte comando para instalar os drivers p/ leitora de cartão:

sudo apt install libccid pcscd
2) Baixe e instale via Software Center os arquivos necessários:

  a) libgdbm3 (Link: <ftp.br.debian.org/debian/pool/main/g/gdbm/libgdbm3_1.8.3-13.1_amd64.deb>);

  b) libpng12-0 (Link <ftp.br.debian.org/debian/pool/main/libp/libpng/libpng12-0_1.2.50-2+deb8u3_amd64.deb>);

  c) SafeSign (Link: <http://www.digitalsigncertificadora.com.br/repositorio/downloads/SafeSignIC3.0.116-x86_64-ub14-tc-admin.deb>;

  d) WebSigner (Link: <https://websigner.softplan.com.br/Downloads/2.5.1/webpki-chrome-64-deb>;

3) Instale no Firefox o plugin do WebSigner (Link: <https://websigner.softplan.com.br>; Para instalar siga as instruções da página.

4) Clique no ícone do WebSigner no canto direito da barra superior do Firefox, e em seguida, clique no botão da direita 'Crypto devices (PKCS #11...)' (o que tem umas engrenagens no ícone), e marque a opção 'libaetpkss.so.3 (Smart cards managed by SafeSign)' e clique em OK.

5) Plugue a leitora com o cartão e proceda com o teste:

  a) Abra o programa SafeSign que você instalou e tente abrir o seu certificado digital.

  b) Abra o eSAJ do seu tribunal local e verifique os requisitos do peticionamento eletrônico: <https://esaj.tjsc.jus.br/petpg/abrirVerificacaoRequisitosPet.do>;
