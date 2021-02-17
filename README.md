# nessus-compliance
Custom Nessus Compliance Scans

Official documentation: https://docs.tenable.com/sccv/Content/AuditFiles.htm

## Audit Files
#### [PSv2.audit](PSv2.audit)
* Detect the presence of PowerShell 2.0 (MicrosoftWindowsPowerShellV2 optional feature)

#### [MicTrayLogCheck.audit](MicTrayLogCheck.audit)
* Detect the presence of MicTray.log keylogging file left by previous versions of Conexant (CVE-2017-8360)
* More information: https://nvd.nist.gov/vuln/detail/CVE-2017-8360

#### [MININTCheck.audit](MININTCheck.audit)
* Detect the presence of leftover MDT deployment file (in the `C:\MININT` folder)

#### [TPMCheck.audit](TPMCheck.audit)
* Detect the presence of a TPM chip


