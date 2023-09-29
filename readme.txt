Passo a Passo de Baixar e Instalar o REDIS

No Linux:
1. Abra o terminal.

2. Atualize seu sistema, se necessário:
sudo apt-get update

3. Instale o Redis usando o gerenciador de pacotes:
sudo apt-get install redis-server

4. O Redis deve ser iniciado automaticamente após a instalação. Você pode verificar o status usando:
sudo systemctl status redis

5. Para iniciar, parar ou reiniciar o Redis manualmente, você pode usar os seguintes comandos:
Iniciar o Redis:
sudo systemctl start redis

Parar o Redis:
sudo systemctl stop redis

Reiniciar o Redis:
sudo systemctl restart redis


