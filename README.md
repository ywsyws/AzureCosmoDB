# Azure Cosmos DB
## Azure-SSIS Integration Runtime[](https://docs.microsoft.com/en-us/azure/data-factory/concepts-integration-runtime#azure-ssis-integration-runtime)

To lift and shift existing SSIS workload, you can create an Azure-SSIS IR to natively execute SSIS packages.

### Azure-SSIS IR network environment[](https://docs.microsoft.com/en-us/azure/data-factory/concepts-integration-runtime#azure-ssis-ir-network-environment)

Azure-SSIS IR can be provisioned in either public network or private network. On-premises data access is supported by joining Azure-SSIS IR to a Virtual Network that is connected to your on-premises network.

### Azure-SSIS IR compute resource and scaling[](https://docs.microsoft.com/en-us/azure/data-factory/concepts-integration-runtime#azure-ssis-ir-compute-resource-and-scaling)

Azure-SSIS IR is a fully managed cluster of Azure VMs dedicated to run your SSIS packages. You can bring your own Azure SQL Database or Managed Instance server to host the catalog of SSIS projects/packages (SSISDB) that is going to be attached to it. You can scale up the power of the compute by specifying node size and scale it out by specifying the number of nodes in the cluster. You can manage the cost of running your Azure-SSIS Integration Runtime by stopping and starting it as you see fit.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI4OTMzNDE2MCw2OTY4NjQ5NDJdfQ==
-->