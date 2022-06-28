# README.md
The contents of this folder is to support a TDD example of ACE and APIC

The structure somewhat needs to be maintained for it to all work properly

The folders structure is as follows;
- ace - sample ACE API deployment that can be deployed via the tekton pipeline
  | - bar - bar file to be deployed/referenced
  | - config - any ACE "Kind: Configuration" that are used consumed  be the bar file
  | - prod - example folder for a production deployment, it contains an example ACE "Kind: IntegrationServer" file
  | - scripts - folder for scripts that are used during the tekton build and deploy process
  | - test - example folder for a test deployment 