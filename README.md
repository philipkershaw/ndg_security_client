ndg_security_client
===================
Package for client-side specific NDG Security components

NDG Security is the security system for the UK Natural Environment Research
Council funded NERC DataGrid.  NDG Security has been developed to 
provide users with seamless federated access to secured resources across NDG 
participating organisations whilst at the same time providing an underlying 
system which is easy to deploy around organisation's pre-existing systems. 

The system has since been further developed in collaboration with the 
US DoE funded Earth System Grid project for the ESG Federation an infrastructure
under development in support of CMIP5 (Coupled Model Intercomparison Project 
Phase 5), a framework for a co-ordinated set of climate model experiments 
which will input into the forthcoming 5th IPCC Assessment Report.

NDG and ESG use a common access control architecture.  OpenID and MyProxy are 
used to support single sign on for browser based and HTTP rich client based 
applications respectively.  SAML is used for attribute query and authorisation
decision interfaces.  XACML is used as the policy engine.  NDG Security has been
re-engineered to use a filter based architecture based on WSGI enabling other 
Python WSGI based applications to be protected in a flexible manner without the 
need to modify application code.
