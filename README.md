# VS2019-Launch-BSB-SQLDatabase(CI/CD)
Demo realizada no evento  [Visual Studio 2019 Launch](https://www.meetup.com/DevelopersBR/events/260461888/)

## Sumário
* [Palestra](#palestra)
* [Integrantes](#integrantes)
* [Instruções](#instrucoes)
* [CI/CD](#ci/cd)

## Palestra
* Como o Azure e Azure DevOps podem levar a integração do seu time  
[VS2019 Launch.pptx](https://github.com/sidneyocirqueira/vs2019-launch-bsb-sqldb/blob/master/ppt/VS2019%20Launch.pptx)

## Integrantes
1. [Renan](https://github.com/renanlq) 
2. [Sidney](https://github.com/sidneyocirqueira)
3. [Yago](https://github.com/yagoluiz)

## Instruções
Instruções para execução do projeto:
* Provisionar Ambiente de Azure SQL Database via [ARM Template](https://github.com/sidneyocirqueira/vs2019-launch-bsb-sqldb/arm) com Power Shell;
* Executar projeto via Visual Studio ou Visual Studio Code

  [Solution](https://github.com/sidneyocirqueira/vs2019-launch-bsb-sqldb/blob/master/VS2019.sln) |
  [SQL Project](https://github.com/sidneyocirqueira/vs2019-launch-bsb-sqldb/blob/master/src/VS2019.Database/VS2019.Database.sqlproj)

## CI/CD
* Realizar via Azure DevOps [Build e Release](https://docs.microsoft.com/en-us/azure/devops/pipelines/?view=azure-devops)

## Referências 
* Azure SQL Database: https://docs.microsoft.com/en-us/azure/sql-database/

* SSDT: https://devblogs.microsoft.com/ssdt/

* SSDT + Visual Studi: https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/SQL-Server-Data-Tools-for-Visual-Studio

* Azure DevOps: https://azure.microsoft.com/en-us/services/devops/

* DevOps Using SQL Server: https://www.microsoft.com/en-us/sql-server/developer-get-started/sql-devops/

* Database DevOps: https://azure.microsoft.com/pt-br/resources/videos/connect-2017-database-devops-with-sql-server-data-tools-and-team-services/
