# NK Extract

Aplicativo da NK Consultoria para extrair relatórios dos sistemas de gestão dos clientes
(Bling, Omie, Tiny, Conta Azul, Sienge, Asaas, Kiwify, Shopify, Nuvemshop e NK FINANCE)
direto para o Excel, na hora ou agendado.

## Baixar

**[⬇ Baixar o NK Extract (Windows)](https://github.com/nkconsultoriatech/nk-extract-instalador/releases/latest/download/NK_Extract_Setup.exe)**

O link sempre baixa a versão mais recente. Funciona no Windows 10 e 11 (64 bits),
inclusive no servidor acessado por área de trabalho remota (RDP).

## Instalar

1. Abra o arquivo `NK_Extract_Setup.exe` que foi baixado.
2. Se o Windows mostrar **"O Windows protegeu o computador"**, clique em
   **Mais informações** e depois em **Executar assim mesmo**. O aviso aparece
   porque o instalador ainda não tem certificado digital; o arquivo é o publicado aqui.
3. Siga o instalador até o fim. O NK Extract abre sozinho.

Não precisa de senha de administrador: o app instala só para o seu usuário do Windows.
Cada pessoa instala no próprio usuário.

## Primeiro uso: entrar na equipe

Os clientes não vêm no instalador. O administrador da equipe cadastra você e passa
**seu usuário**, uma **senha provisória** e, se quiser, um **convite** (arquivo `.nkconvite`).

1. No NK Extract, abra **Configurações → Equipe → Entrar numa equipe**.
2. Clique em **Abrir convite...** e escolha o arquivo recebido (ou informe a pasta da
   equipe que o administrador passou).
3. Digite seu usuário e a senha provisória e clique em **Entrar**.
4. Crie a sua senha. Só você vai saber; o administrador não vê.

Pronto: os clientes aparecem já conectados, sem recadastrar nada. O app guarda o seu
login neste usuário do Windows e não pede a senha toda vez.

> O computador precisa acessar a pasta da equipe (a mesma que aparece no convite).
> Se aparecer "sem acesso à pasta da equipe", confira a rede ou a VPN.

Sem equipe? Também dá para receber clientes num arquivo `.nkclientes` com senha:
**Clientes → Importar...**

## No dia a dia

- **Extrações:** escolha o cliente, marque os relatórios, o período e clique em **Extrair**.
- **Clientes:** o que você cadastra, altera ou conecta aparece para toda a equipe.
  Se outra pessoa alterou o mesmo cliente antes, o app avisa e mostra a versão nova.
- **Agendamentos:** os da equipe rodam sozinhos no servidor, no horário, mesmo sem
  ninguém conectado, e os arquivos caem na pasta de cada cliente. Só administradores
  criam e alteram; todos veem o resultado.
- **Saúde dos clientes:** mostra conexões vencidas, falhas e pastas com problema.

## Dúvidas comuns

- **Esqueci minha senha da equipe:** peça ao administrador **Redefinir senha** em
  Pessoas da equipe; você entra com a provisória e cria outra.
- **O app pediu para "Entrar de novo":** sua senha foi trocada em outro computador.
  Entre com a senha nova em Configurações → Equipe.
- **"Reconectar" num cliente:** a autorização daquele sistema venceu. Abra o cliente
  na aba Clientes e clique em Conectar.
- **Vou sair da empresa / trocar de computador:** o administrador remove ou cadastra
  você de novo; seus dados de acesso não ficam presos a um PC.

## Atualizações

O próprio app avisa quando sai uma versão nova: clique em **Atualizar agora**.
Não é preciso baixar de novo por aqui.

Versões anteriores e o que mudou em cada uma: [Releases](https://github.com/nkconsultoriatech/nk-extract-instalador/releases).
