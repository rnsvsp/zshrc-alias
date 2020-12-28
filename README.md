# zshrc-alias
# Configurações Mínimas para ZSHRC e BASHRC
# Insira as linhas abaixo no final do seu arquivo .zshrc ou .bashrc
# Sempre que fizer alguma alteração em seu arquivo, dê o comando, source ~/.zshrc (ou .bashrc ou .zprofile)

# Atalhos para terminal
alias res="reset" # Limpa a tela do terminal por inteira, assim podem ficar sem tantos códigos a mostra
alias szsh="source ~/.zshrc" # Reinicia o arquivo .zshrc para validar novas alterações feitas no mesmo
alias sbash="source ~/.bashrc" # Reinicia o arquivo .bashrc para validar novas alterações feitas no mesmo
alias cls="clear" # Limpa o terminal adicionando espaços acima

# Atalhos para utilização do brew, gerenciador de pacotes
alias instalar="brew cask install" # Utilizado para instalar um programa pelo brew
alias remover="brew cask uninstall" # Utilizado para desinstalar um programa instalado pelo brew

# Atalhos de instalação do programas disponíveis no repositório do brew
alias vscodeinstall="brew cask install virtual-studio-code" # Instalando o VS Code
alias transmission="brew cask install transmission-cli" # Instalando o Transmission
alias firefox="brew cask install firefox" # Instalando o Firefox
# Para adicionar mais programas, consulte o repositório oficinal do BREW e crie seus atalhos, link: https://formulae.brew.sh/formula/

# Atalhos para Flutter, aumento de produtividade
#alias fld="flutter doctor" # Verifica status de instalação do flutter
#alias flv="flutter doctor -v" # Verifica pendências de libs para utilização do flutter com mais detalhes
#alias flr="flutter run" # Comando para rodar seu aplicativo em desenvolvimento, necessário estar dentro da pasta do App
#alias flc="flutter emulators --create" # [--name nome_do_emulador]

# Atalhos para Dart, instalação do interpretador
alias darttap="brew tap dart-lang/dart" # Adicionado o repositório de terceiros do interpretador ao brew
alias dartinstall="brew install dart" # Instala o interpretador
