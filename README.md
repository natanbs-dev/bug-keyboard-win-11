# bug-keyboard-win-11

Esse problema no Windows 11, onde o teclado funciona normalmente em aplicativos, mas não responde ao tentar digitar no Menu Iniciar ou na barra de pesquisa, é um bug conhecido que pode estar relacionado a atualizações recentes do sistema ou a falhas nos serviços de entrada de texto.​
Tecnoblog
🛠️ Soluções recomendadas
1. Reiniciar o processo de pesquisa do Windows

Encerrar e reiniciar o processo responsável pela pesquisa pode resolver o problema:

    Pressione Ctrl + Shift + Esc para abrir o Gerenciador de Tarefas.

    Vá até a aba Detalhes.

    Localize o processo SearchHost.exe.

    Clique com o botão direito sobre ele e selecione Finalizar tarefa.

    O processo será reiniciado automaticamente.​
    Microsoft Learn

2. Executar o solucionador de problemas de pesquisa e indexação

O Windows possui uma ferramenta integrada para diagnosticar e corrigir problemas de pesquisa:

    Pressione Windows + R, digite msdt.exe -ep WindowsHelp id SearchDiagnostic e pressione Enter.

    Siga as instruções na tela para identificar e corrigir possíveis falhas.​
    Microsoft Learn

3. Reiniciar o serviço de cache de fontes do Windows

Problemas no serviço de cache de fontes podem afetar a funcionalidade da pesquisa:

    Pressione Windows + R, digite services.msc e pressione Enter.

    Na lista de serviços, localize Serviço de Cache de Fontes do Windows.

    Clique com o botão direito sobre ele e selecione Parar.

    Aguarde alguns segundos, clique novamente com o botão direito e selecione Iniciar.​
    Microsoft Learn

4. Verificar e instalar atualizações do Windows

A Microsoft frequentemente lança correções para bugs conhecidos:

    Vá em Configurações > Windows Update.

    Clique em Verificar se há atualizações.

    Instale todas as atualizações disponíveis e reinicie o computador.​
    Microsoft Learn+1AVG.com+1

5. Registrar novamente os pacotes de aplicativos do Windows

Reinstalar os pacotes de aplicativos pode corrigir falhas no Menu Iniciar e na pesquisa:

    Clique com o botão direito no botão Iniciar e selecione Terminal do Windows (Admin).

    Digite o seguinte comando e pressione Enter:

    Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}

YouTube+4Tecnoblog+4Tudo Celular+4
6. Criar um novo perfil de usuário

Se o problema persistir, criar um novo perfil de usuário pode ser uma solução:

    Vá em Configurações > Contas > Família e outros usuários.

    Clique em Adicionar outra pessoa a este PC.

    Siga as instruções para criar uma nova conta de usuário.

    Faça login com a nova conta e verifique se o problema foi resolvido.​

7. Utilizar o teclado na tela como alternativa temporária

Enquanto o problema não é resolvido, você pode utilizar o teclado virtual:

    Pressione Windows + Ctrl + O para ativar o teclado na tela.

    Use-o para digitar na barra de pesquisa ou no Menu Iniciar.​
    AVG.com
