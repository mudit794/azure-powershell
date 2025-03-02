<!--
    Please leave this section at the top of the change log.

    Changes for the upcoming release should go under the section titled "Upcoming Release", and should adhere to the following format:

    ## Upcoming Release
    * Overview of change #1
        - Additional information about change #1
    * Overview of change #2
        - Additional information about change #2
        - Additional information about change #2
    * Overview of change #3
    * Overview of change #4
        - Additional information about change #4

    ## YYYY.MM.DD - Version X.Y.Z (Previous Release)
    * Overview of change #1
        - Additional information about change #1
-->
## Upcoming Release
* Adding CRUD commands for ADF V2 data flow: Set-AzDataFactoryV2DataFlow, Remove-AzDataFactoryV2DataFlow, and Get-AzDataFactoryV2DataFlow.
* Adding action commands for ADF V2 data flow debug Session: Start-AzDataFactoryV2DataFlowDebugSession, Get-AzDataFactoryV2DataFlowDebugSession, Add-AzDataFactoryV2DataFlowDebugSessionPackage, Invoke-AzDataFactoryV2DataFlowDebugSessionCommand and Stop-AzDataFactoryV2DataFlowDebugSession.
* Update ADF .Net SDK version to 4.2.0

## Version 1.3.0
* Adding 3 new commands for ADF V2 - Add-AzDataFactoryV2TriggerSubscription, Remove-AzDataFactoryV2TriggerSubscription, and Get-AzDataFactoryV2TriggerSubscriptionStatus
* Updated ADF .Net SDK version to 4.1.3


## Version 1.2.0
* Fix typo to capitalize "Windows" in 'New-AzDataFactoryEncryptValue" documentation
* Fixed miscellaneous typos across module
* Updated ADF .Net SDK version to 4.1.2
* Add parameter "DataProxyIntegrationRuntimeName", "DataProxyStagingLinkedServiceName" and "DataProxyStagingPath" for "Set-AzureRmDataFactoryV2IntegrationRuntime" cmd to enable set up Self-Hosted Integration Runtime as a proxy for SSIS Integration Runtime
* Updated PSTriggerRun to show the triggered pipelines, message and properties, and PSActivityRun to show the activity type

## Version 1.1.3
* Updated ADF .Net SDK version to 4.1.0
* Fix typo in documentation for `Get-AzDataFactoryV2PipelineRun`

## Version 1.1.2
* Updating the output of get activity runs, get pipeline runs, and get trigger runs ADF cmdlets to support Select-Object pipe.

## Version 1.1.1
* Add SsisProperties if NodeCount not null for managed integration runtime.

## Version 1.1.0
* Updated ADF .Net SDK version to 3.0.2
* Updated Set-AzDataFactoryV2 cmdlet with extra parameters for RepoConfiguration related settings.

## Version 1.0.2
* Updated ADF .Net SDK version to 3.0.1

## Version 1.0.1
* Updated ADF .Net SDK version to 3.0.0

## Version 1.0.0
* General availability of `Az.DataFactory` module
* Removed -LinkedServiceName parameter from Get-AzDataFactoryV2ActivityRun
