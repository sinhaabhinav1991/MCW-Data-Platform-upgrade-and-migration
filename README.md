# Data Platform upgrade and migration

World Wide Importers has experienced significant growth in the last few years. In addition to predictable growth, they’ve had a substantial amount of growth in the data they store in their data warehouse. Their data warehouse is starting to show its age; slowing down during extract, transform, and load (ETL) operations and during critical queries. It was built on SQL Server 2008 R2 Standard Edition.

Their CIO has recently read about new performance enhancements of Azure SQL Database and SQL Server 2017. She is excited about the potential performance improvements related to clustered ColumnStore indexes. She is also hoping that table compression will improve performance and backup times.

The company is concerned about upgrading their database to Azure SQL Database or SQL Server 2017. The data warehouse has been successful for a long time. As it has grown, it has filled with data, stored procedures, views, and security. They want assurance that if it moves its data store, it won’t run into any incompatibilities with the storage engine of Azure SQL Database or SQL Server 2017.

The CIO would like a proof of concept of a data warehouse move, as well as proof that the new technology will help ETL and query performance.

## Target audience

- Application developer
- SQL Developer
- Database Administrator

## Abstract

### Workshop

In this workshop, you will gain a better understanding of how to conduct a site analysis for a customer to compare cost, performance, and level of effort required to migrate from Oracle to SQL Server. You will evaluate the dependent applications and reports that will need to be updated and come up with a migration plan. In addition, you will design and build a proof of concept (POC) and help the customer take advantage of new SQL Server features to improve performance and resiliency, as well as explore ways to migrate from an old version of SQL Server, to the latest version and consider the impact of migrating from on-premises to the cloud.

At the end of this workshop, you will be better able to conduct a site analysis for compare cost, performance, and level of effort required to migrate from Oracle to SQL Server.

### Whiteboard design session

In this whiteboard design session, you will work with a group to design a proof of concept (POC) for conducting a site analysis for a customer to compare cost, performance, and level of effort required to migrate from Oracle to SQL Server. You will evaluate the dependent applications and reports that will need to be updated and come up with a migration plan. In addition, you will look at ways to help the customer take advantage of new SQL Server features to improve performance and resiliency, as well as explore ways to migrate from an old version of SQL Server to the latest version and consider the impact of migrating from on-premises to the cloud.

At the end of this whiteboard design session, you will be better able to design a database migration plan and implementation.

### Hands-on lab

In this hands-on lab, you will implement a proof of concept (POC) for conducting a site analysis for a customer to compare cost, performance, and level of effort required to migrate from Oracle to SQL Server. You will evaluate the dependent applications and reports that will need to be updated and come up with a migration plan. In addition, you will help the customer take advantage of new SQL Server features to improve performance and resiliency, as well as conduct a migration from an old version of SQL Server to Azure SQL Database.

At the end of this hands-on lab, you will be better able to design and build a database migration plan and implement any required application changes associated with changing database technologies.

## Azure services and related products

- Azure App Services
- Azure Database Migration Service (DMS)
- Azure SQL Database
- Azure SQL Data Warehouse
- Data Migration Assistant (DMA)
- SQL Server 2008 R2 and 2017
- SQL Server Management Studio (SSMS)
- SQL Server Migration Assistant (SSMA)
- Visual Studio 2017

## Azure solution

Data Modernization to Azure

## Related references

[MCW](https://github.com/Microsoft/MCW)