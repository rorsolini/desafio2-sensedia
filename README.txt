# desafio2-sensedia
Desafio Docker
Com o docker instalado e executado na máquina, dar os seguintes comandos no TL:
docker pull nginx #clicar enter para fazer a instalação do NGIX no docker
No TL, procurar a pasta que deseja criar o HTML (eu utilizei a pasta C:\Users\user\Desktop\desafio2-sensedia)
Criar o HTML, salvar e executar o seguinte comando:
docker run -v C:\Users\user\Desktop\desafio2-sensedia:/usr/share/nginx/html -p 80:80 -d nginx
O terminal confirmará com um código. A partir daí, é só fazer o teste em localhost no navegador.
