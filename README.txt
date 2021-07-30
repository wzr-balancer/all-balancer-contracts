Deployments Required:

Balancer:
========================
From BActions.sol
	 BActions

From CRPFactory.sol:	
	Libraries:
		BalancerSafeMath
		RightsManager
		SmartPoolManager

	Main contract:
		CRPFactory	
 
 (on remix IDE deploy CRPFactory and
  it automatically deploy the libraries)
		
	
From ExchangeProxy.sol
	ExchangeProxy


Dapphub:
========================

From ProxyRegistry.sol
	DSProxyFactory
	ProxyRegistry( DSProxyFactory )


If is required:
==================
Multicall from https://github.com/makerdao/multicall


Also need the $WETH equivalent