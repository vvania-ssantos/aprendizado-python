🔹 Primeira vez no projeto (inicializar e conectar)
git init                        # inicia o repositório Git na pasta
git branch -M main              # define o nome da branch principal como main
git remote add origin URL_DO_REPO   # conecta ao GitHub (só 1 vez)

🔹 Ciclo básico de salvar mudanças
git status                      # mostra o que foi alterado
git add NOME_DO_ARQUIVO         # adiciona arquivo específico
git add .                       # adiciona TODOS os arquivos alterados
git commit -m "Mensagem"        # salva as alterações localmente
git push origin main            # envia pro GitHub


🔹 Consultas rápidas
git log                         # mostra histórico de commits
git remote -v                   # mostra a URL do repositório conectado
git branch                      # mostra em qual branch você está

🔹 Errei algo? (sem pânico 😅)
git reset HEAD~1                # desfaz o último commit (mas mantém os arquivos)
git checkout -- NOME_ARQUIVO    # volta o arquivo alterado para a última versão salva

💡 Dica de ouro: sempre antes de git add, rode um git status pra confirmar o que vai subir pro GitHub.


Adicionar os arquivos ao controle de versão:
git add .

Fazer o primeiro commit:
git commit -m "Primeiro commit - aprendizados em Python"

Enviar para o GitHub:
git push -u origin main

