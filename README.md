# Tom.DDD2

learn NLayerApp

----------
1.Presentaion
2.DistributedServices
	>MainBoundedContext>DistributedServices.MainBoundedContext.proj>BankingModuleService(ApiConroller,IBankingModuleService),ERPModuleService
3.Application
	>MainBoundedContext>Application.MainBoundedContext,Application.MainBoundedContext.DTO>BankingModule>BankAppService
4.Domain
	>Domain.MainBoundedContext>BankingModule>Aggregates>BankAccountAgg
5.Infranstructure
	>Infrastructure.Data.MainBoundedContext>BankingModule>Repositories>BankAccountRepository

Presentaion >>DistributedServices.BankingModuleService >>Application.IBankAppService >>_bankAccountRepository.Add()
Mapper from Dto to Entity