# Atividade-Projetos-Calculadora
Análise do erro de Bundle da aplicação

Até a aula 55 (componente botão#02) estava funcionando o emulador que utilizo no dispositivo fisico porém eu parei o estudo na metade da aula para continuar o outro dia
e quando foi outro dia esqueci em casa o cabo USB que eu conectava no notebook para ativar o emulador no dispositivo fisico e decidi seguir a documentação do react native para ativar o emulador via WIFI e após isso executei o comando adb shell input keyevent 82 para abrir o menu dev (82 sendo o código da tecla Menu). porém não achei essa opção na tela que abriu no dispotivo dai eu desisti e fui buscar meu cabo usb porém quando eu conectei o cabo usb e dei o comando para iniciar o emulador como de costume NPX REACT-NATIVE RUN-ANDROID o projeto abria apenas uma tela em branco no dispositivo e no NODE.JS apresentava o seguinte erro na hora de dar o BUNDLE -   


Invariant Violation: No dimension set for key windows 
Invariant Violation: Module AppRegistry is not a registered callable module (calling runApplication)
Invariant Violation: Module AppRegistry is not a registered callable module (calling runApplication)

Estarei anexando a foto do erro.

