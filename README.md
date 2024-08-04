# Desafio | Analista de Qualidade de Software Júnior

Aqui você irá encontrar o caminho percorrido para conclusão do desafio proposto para a vaga de QA na BEEDOO AI learning.

## O desenvolvimento das User Storys
No começo do desafio, optei por reconhecer e tirar as primeiras impressões do site de cursos. 
Com uma visão macro das principais funcionalidades apresentadas, **Criar Curso**, **Listar Curso** e **Excluir Curso**. Foi possível criar as User Storys de forma clara e objetiva.   
Pensando na qualidade e usabilidade do sistema criei alguns **Critérios de aceite**, assim obtive um melhor desenvolvimento e direcionamento dos casos de teste.

## Feature 'Cadastro de curso'
User Story

> Como um usuário do sistema  
> Eu quero cadastrar um curso  
> Para que os usuários possam ver e se inscrever nos cursos oferecidos.

 Critérios de aceite 
- Campos obrigatórios:
  - Nome do curso
  - Descrição do curso
  - Data de Inicio
  - Data de fim
  - Tipo do curso
    - Endereço
    - Link de inscrição    
  - Número de vagas
- Campos não obrigatórios:
  - Url da imagem de capa   
- O Campo 'Nome do curso' deve conter no máximo 50 caracteres:  
- O Campo 'Descrição do curso' deve conter no mínimo 240 caracteres:  
- O campo 'Data de início' deve ser posterior a data vigente:  
- O campo 'Data de fim' deve ser posterior ao campo 'Data de início':
- O campo 'Número de vagas' deve receber valores maiores que '0':   
- Se o curso for presencial deve o campo endereço se torna obrigatório:
- Se o curso for online o campo link se torna obrigatório: 
  



## Feature 'Listar cursos'
User Story

> Como um usuário do sistema  
> Eu quero acesso a uma lista de cursos já criados  
> Para que eu possa visualizar os cursos disponíveis.

 Critérios de aceite 
- Os cursos listados devem conter os seguintes campos visíveis:
  - Nome do curso
  - Descrição do curso
  - Data de inicio 
  - Data de fim
  - Tipo do curso
  - Número de vagas
  - Imagem (Url da imagem de capa)
- Os cursos listados devem estar visíveis de forma coesa e organizada com margens padrões para todos:

## Feature 'Excluir curso'
User Story

> Como um usuário do sistema  
> no campo de listar cursos  
> eu quero poder excluir um curso já cadastrado.

Critérios de aceite 
- Deve ser possível excluir um curso cadastrado.

## Link Casos de teste
Aqui você encontrará os casos de testes executados.  
[Casos de teste](https://docs.google.com/spreadsheets/d/1C6WctQCY5jUOLxOx7GpR84PSLG5EnNCQ/edit?usp=drive_link&ouid=114076122423645119680&rtpof=true&sd=true)

## Link Evidencias de teste
Aqui você encontrará as evidencias do caso de teste.  
[Evidencias](https://drive.google.com/drive/folders/1309tkYTQTmgwqC6e0mkZI48FO_FhuF7Q?usp=sharing)
