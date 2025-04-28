# app

Gympass style app

# RFs (requisitos funcionais)

- [ ] Deve ser possivel se cadastrar
- [ ] Deve ser possivel se autenticar
- [ ] Deve ser possivel obter o perfil de um usuario logado
- [ ] Deve ser possivel obter um numero de check-ins realizado pelo usuario
- [ ] Deve ser possivel o usuario buscar academias proximas
- [ ] Deve ser possivel o usuario buscar academias pelo nome
- [ ] Deve ser possivel o usuario realizar check-in em uma academia
- [ ] Deve ser possivel validar o check-in de um usuario
- [ ] Deve ser possivel cadastrar uma academia

## RNs (regras de negocio)

- [ ] O usuario não deve poder se cadastrar com um email duplicado
- [ ] O usuario não pode fazer 2 check-ins no mesmo dia
- [ ] O usuario não pode fazer checkín se não estiver perto (100m) da academia
- [ ] O check-in só pode ser validado até 20 minutos após criado
- [ ] O check-in só pode ser validado por administradores
- [ ] A academmia só pode ser cadastrada por administradores

## RNF (requisitos nn funcionais)

- [ ] A senha do usuario precisa estar criptografada
- [ ] Os dados da aplicação precisam estar persistidos em um banco postgresSQL
- [ ] Todas as listas de dados precisam estar paginados com 20 itens po pagina
- [ ] O usuario deve ser identificado por um JWT (JSON web token)