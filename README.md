
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>PHPAfterShell - Emergency Security Alert</title>
</head>

<body style="margin:0;padding:0;background:#f3f4f6;font-family:Arial,Helvetica,sans-serif;color:#242424;">

<table role="presentation" width="100%" cellpadding="0" cellspacing="0" border="0" style="background:#f3f4f6;">
<tr>
<td align="center" style="padding:24px 12px;">

<table role="presentation" width="100%" cellpadding="0" cellspacing="0" border="0" style="max-width:760px;background:#ffffff;border:1px solid #dddddd;">

<!-- HEADER -->
<tr>
<td style="background:#202b3a;padding:24px 28px;color:#ffffff;">

<div style="font-size:12px;font-weight:bold;letter-spacing:1px;color:#ffd08a;">
TLP:AMBER+STRICT | EMERGENCY | VULNERABILITY ALERT
</div>

<h1 style="font-size:24px;margin:12px 0 8px;color:#ffffff;">
PHP / PHPAfterShell
</h1>

<div style="font-size:16px;color:#ffffff;">
Multiple Critical Vulnerabilities — Remote Code Execution and Privilege Escalation
</div>

</td>
</tr>

<!-- EMERGENCY BANNER -->
<tr>
<td style="padding:16px 28px;background:#fff0ed;border-bottom:3px solid #c62828;">
<strong style="font-size:17px;color:#b42318;">
EMERGENCY — Immediate assessment and remediation required
</strong>
</td>
</tr>

<!-- INTRODUCTION -->
<tr>
<td style="padding:26px 28px 12px;font-size:14px;line-height:1.7;">

<p>Dear Team, Dear Partners,</p>

<p>
We would like to warn you about multiple
<strong style="color:#b42318;">Emergency vulnerabilities</strong>
affecting <strong>PHP</strong>, collectively referred to
as <strong>PHPAfterShell</strong>.
</p>

<p>
Successful exploitation of certain vulnerabilities may
allow unauthenticated remote attackers to execute
arbitrary PHP code, corrupt memory, modify files,
compromise application sessions, or escalate privileges
on affected systems.
</p>

<!-- VULNERABILITY SUMMARY -->
<table width="100%" cellpadding="9" cellspacing="0" border="0" style="border-collapse:collapse;font-size:13px;">

<tr style="background:#263445;color:#ffffff;">
<th align="left" style="border:1px solid #cbd5e1;">Bulletin</th>
<th align="center" style="border:1px solid #cbd5e1;">CVSS</th>
<th align="left" style="border:1px solid #cbd5e1;">Description</th>
<th align="left" style="border:1px solid #cbd5e1;">Type</th>
</tr>

<tr style="background:#f8fafc;">
<td style="border:1px solid #cbd5e1;font-weight:bold;">
<a href="https://www.cve.org/CVERecord?id=CVE-2026-126714" style="color:#175cd3;">CVE-2026-126714</a>
</td>
<td align="center" style="border:1px solid #cbd5e1;background:#c62828;color:#ffffff;font-weight:bold;font-size:17px;">9.2</td>
<td style="border:1px solid #cbd5e1;">
Time-of-check Time-of-use (TOCTOU) vulnerability potentially allowing arbitrary code execution with PHP worker privileges.
</td>
<td style="border:1px solid #cbd5e1;">Privilege Escalation / RCE</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;font-weight:bold;">
<a href="https://www.cve.org/CVERecord?id=CVE-2026-115560" style="color:#175cd3;">CVE-2026-115560</a>
</td>
<td align="center" style="border:1px solid #cbd5e1;background:#c62828;color:#ffffff;font-weight:bold;font-size:17px;">9.2</td>
<td style="border:1px solid #cbd5e1;">
Improper input validation potentially resulting in remote code execution, file modification, session corruption or denial of service.
</td>
<td style="border:1px solid #cbd5e1;">RCE / DoS</td>
</tr>

<tr style="background:#f8fafc;">
<td style="border:1px solid #cbd5e1;font-weight:bold;">
<a href="https://www.cve.org/CVERecord?id=CVE-2026-129182" style="color:#175cd3;">CVE-2026-129182</a>
</td>
<td align="center" style="border:1px solid #cbd5e1;background:#c62828;color:#ffffff;font-weight:bold;font-size:17px;">9.2</td>
<td style="border:1px solid #cbd5e1;">
Use-after-free vulnerability potentially resulting in memory corruption and remote code execution.
</td>
<td style="border:1px solid #cbd5e1;">RCE</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;font-weight:bold;">
<a href="https://www.cve.org/CVERecord?id=CVE-2026-129289" style="color:#175cd3;">CVE-2026-129289</a>
</td>
<td align="center" style="border:1px solid #cbd5e1;background:#c62828;color:#ffffff;font-weight:bold;font-size:17px;">9.2</td>
<td style="border:1px solid #cbd5e1;">
Inconsistent interpretation of HTTP requests potentially allowing execution of attacker-controlled PHP code under specific deployment conditions.
</td>
<td style="border:1px solid #cbd5e1;">Privilege Escalation / RCE</td>
</tr>

<tr style="background:#f8fafc;">
<td style="border:1px solid #cbd5e1;font-weight:bold;">
<a href="https://www.cve.org/CVERecord?id=CVE-2026-129474" style="color:#175cd3;">CVE-2026-129474</a>
</td>
<td align="center" style="border:1px solid #cbd5e1;background:#c62828;color:#ffffff;font-weight:bold;font-size:17px;">9.2</td>
<td style="border:1px solid #cbd5e1;">
Use-after-free vulnerability potentially allowing remote code execution on affected PHP 8.5 deployments.
</td>
<td style="border:1px solid #cbd5e1;">RCE</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;font-weight:bold;">
<a href="https://www.cve.org/CVERecord?id=CVE-2026-129481" style="color:#175cd3;">CVE-2026-129481</a>
</td>
<td align="center" style="border:1px solid #cbd5e1;background:#c62828;color:#ffffff;font-weight:bold;font-size:17px;">9.2</td>
<td style="border:1px solid #cbd5e1;">
Use-after-free vulnerability affecting session cleanup, potentially resulting in memory corruption, PHP worker crashes or remote code execution.
</td>
<td style="border:1px solid #cbd5e1;">RCE</td>
</tr>

<tr style="background:#f8fafc;">
<td style="border:1px solid #cbd5e1;font-weight:bold;">
<a href="https://www.cve.org/CVERecord?id=CVE-2026-129496" style="color:#175cd3;">CVE-2026-129496</a>
</td>
<td align="center" style="border:1px solid #cbd5e1;background:#c62828;color:#ffffff;font-weight:bold;font-size:17px;">9.2</td>
<td style="border:1px solid #cbd5e1;">
Use-after-free vulnerability potentially allowing unauthenticated remote attackers to crash PHP workers or execute arbitrary code with their privileges.
</td>
<td style="border:1px solid #cbd5e1;">Privilege Escalation / RCE</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;font-weight:bold;">
<a href="https://www.cve.org/CVERecord?id=CVE-2026-129291" style="color:#175cd3;">CVE-2026-129291</a>
</td>
<td align="center" style="border:1px solid #cbd5e1;background:#e65100;color:#ffffff;font-weight:bold;font-size:17px;">8.8</td>
<td style="border:1px solid #cbd5e1;">
Use-after-free vulnerability potentially resulting in local privilege escalation.
</td>
<td style="border:1px solid #cbd5e1;">Privilege Escalation</td>
</tr>

</table>

<p>
<strong>Severity:</strong>
<span style="background:#b42318;color:#ffffff;padding:5px 10px;font-weight:bold;">EMERGENCY</span>
</p>

</td>
</tr>

<!-- CONTEXT -->
<tr>
<td style="padding:10px 28px;font-size:14px;line-height:1.7;">

<h2 style="font-size:17px;color:#263445;border-bottom:2px solid #e2e8f0;padding-bottom:8px;">Context</h2>

<p>
Multiple security vulnerabilities have been identified
in PHP, affecting several supported release branches
and potentially exposing web applications to remote
code execution, memory corruption, denial of service
and privilege escalation.
</p>

<p>
The vulnerabilities involve several components of
the PHP runtime, including memory management,
session handling, HTTP request processing and
PHP FastCGI Process Manager (PHP-FPM).
</p>

<p>
Depending on the affected component and deployment
configuration, successful exploitation may allow an
attacker to execute arbitrary code with the privileges
of the PHP worker process.
</p>

<p>
Internet-facing PHP applications, shared hosting
environments, PHP-FPM deployments and applications
processing untrusted user input should be prioritized
for immediate assessment.
</p>

<p>
Actual exploitability depends on the PHP version,
application behavior, enabled features and underlying
web server configuration.
</p>

<h3 style="font-size:15px;color:#263445;">
Vulnerability Details
</h3>

<p>
<strong>CVE-2026-126714:</strong>
A race condition affecting session handling may
result in arbitrary code execution under specific
application and session-processing conditions.
</p>

<p>
<strong>CVE-2026-115560:</strong>
Improper input validation may lead to remote code
execution, unauthorized file modification, session
corruption or denial of service.
</p>

<p>
<strong>CVE-2026-129182:</strong>
A use-after-free condition may cause memory corruption
and potentially remote code execution in affected
PHP versions.
</p>

<p>
<strong>CVE-2026-129289:</strong>
Inconsistent HTTP request processing may result in
execution of attacker-controlled PHP code.
Deployments using persistent FastCGI backend
connections require particular attention.
</p>

<p>
<strong>CVE-2026-129474:</strong>
A use-after-free vulnerability associated with
fatal-error processing may result in memory corruption
and potentially remote code execution, depending on
application behavior.
</p>

<p>
<strong>CVE-2026-129481:</strong>
A use-after-free vulnerability during session cleanup
may corrupt memory, crash a reused PHP worker or
potentially allow remote code execution.
</p>

<p>
<strong>CVE-2026-129496:</strong>
A use-after-free vulnerability may allow an
unauthenticated remote attacker to crash affected
PHP workers or execute arbitrary code with their
privileges.
</p>

<p>
<strong>CVE-2026-129291:</strong>
A use-after-free vulnerability affecting specific
PHP-FPM configurations may allow local privilege
escalation. Unlike the remote vulnerabilities,
exploitation requires an existing local execution
capability and additional deployment conditions.
</p>

</td>
</tr>

<!-- AFFECTED VERSIONS -->
<tr>
<td style="padding:10px 28px;font-size:14px;line-height:1.6;">

<h2 style="font-size:17px;color:#263445;border-bottom:2px solid #e2e8f0;padding-bottom:8px;">
Affected Versions and Patches
</h2>

<p>
The following PHP security releases address the
reported vulnerabilities, depending on the affected
release branch.
</p>

<table width="100%" cellpadding="10" cellspacing="0" border="0" style="border-collapse:collapse;font-size:13px;">

<tr style="background:#263445;color:#ffffff;">
<th align="left" style="border:1px solid #cbd5e1;">Affected Release Branch</th>
<th align="left" style="border:1px solid #cbd5e1;">Fixed Version</th>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">PHP 8.2.x before 8.2.36</td>
<td style="border:1px solid #cbd5e1;background:#eaf5ec;">
<a href="https://www.php.net/ChangeLog-8.php#8.2.36" style="color:#175cd3;font-weight:bold;">8.2.36</a>
</td>
</tr>

<tr style="background:#f8fafc;">
<td style="border:1px solid #cbd5e1;">PHP 8.3.x before 8.3.37</td>
<td style="border:1px solid #cbd5e1;background:#eaf5ec;">
<a href="https://www.php.net/ChangeLog-8.php#8.3.37" style="color:#175cd3;font-weight:bold;">8.3.37</a>
</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">PHP 8.4.x before 8.4.28</td>
<td style="border:1px solid #cbd5e1;background:#eaf5ec;">
<a href="https://www.php.net/ChangeLog-8.php#8.4.28" style="color:#175cd3;font-weight:bold;">8.4.28</a>
</td>
</tr>

<tr style="background:#f8fafc;">
<td style="border:1px solid #cbd5e1;">PHP 8.5.x before 8.5.13</td>
<td style="border:1px solid #cbd5e1;background:#eaf5ec;">
<a href="https://www.php.net/ChangeLog-8.php#8.5.13" style="color:#175cd3;font-weight:bold;">8.5.13</a>
</td>
</tr>

</table>

<p>
PHP <strong>8.6.0</strong>, released on November 19, 2026,
also includes the fixes according to the reference alert.
</p>

<p>
<a href="https://www.php.net/ChangeLog-8.php#8.6.0" style="color:#175cd3;">
PHP 8.6.0 Release Information
</a>
</p>

<p>
<strong>Important:</strong> Not all vulnerabilities affect
every PHP release branch. Consult the detailed patch
matrix below and the applicable vendor advisory.
</p>

<!-- CVE PATCH MATRIX -->
<h3 style="font-size:15px;color:#263445;margin-top:24px;">
Detailed Patch Matrix per CVE
</h3>

<table width="100%" cellpadding="9" cellspacing="0" border="0" style="border-collapse:collapse;font-size:12px;">

<tr style="background:#263445;color:#ffffff;">
<th align="left" style="border:1px solid #cbd5e1;">CVE</th>
<th style="border:1px solid #cbd5e1;">PHP 8.2</th>
<th style="border:1px solid #cbd5e1;">PHP 8.3</th>
<th style="border:1px solid #cbd5e1;">PHP 8.4</th>
<th style="border:1px solid #cbd5e1;">PHP 8.5</th>
<th style="border:1px solid #cbd5e1;">PHP 8.6</th>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">CVE-2026-126714</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.2.36</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.3.37</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.4.28</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.5.13</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.6.0</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">CVE-2026-115560</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.2.36</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.3.37</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.4.28</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.5.13</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.6.0</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">CVE-2026-129182</td>
<td align="center" style="border:1px solid #cbd5e1;background:#f1f5f9;">—</td>
<td align="center" style="border:1px solid #cbd5e1;background:#f1f5f9;">—</td>
<td align="center" style="border:1px solid #cbd5e1;background:#f1f5f9;">—</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.5.13</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.6.0</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">CVE-2026-129289</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.2.36</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.3.37</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.4.28</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.5.13</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.6.0</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">CVE-2026-129474</td>
<td align="center" style="border:1px solid #cbd5e1;background:#f1f5f9;">—</td>
<td align="center" style="border:1px solid #cbd5e1;background:#f1f5f9;">—</td>
<td align="center" style="border:1px solid #cbd5e1;background:#f1f5f9;">—</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.5.13</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.6.0</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">CVE-2026-129481</td>
<td align="center" style="border:1px solid #cbd5e1;background:#f1f5f9;">—</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.3.37</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.4.28</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.5.13</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.6.0</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">CVE-2026-129496</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.2.36</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.3.37</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.4.28</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.5.13</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.6.0</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">CVE-2026-129291</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.2.36</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.3.37</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.4.28</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.5.13</td>
<td align="center" style="border:1px solid #cbd5e1;background:#eaf5ec;">8.6.0</td>
</tr>

</table>

<p style="font-size:12px;color:#64748b;">
Green cells indicate the fixed releases listed in the
reference alert. A dash indicates that no fixed release
for that branch is listed in the supplied patch matrix.
Consult the vendor advisory to confirm applicability.
</p>

<!-- RED HAT -->
<h3 style="font-size:15px;color:#263445;margin-top:24px;">
Red Hat Enterprise Linux
</h3>

<p>
Red Hat has issued the following security bulletin:
</p>

<p>
<a href="https://access.redhat.com/security/vulnerabilities/RHSB-2026-020" style="color:#175cd3;font-weight:bold;">
RHSB-2026-020 — PHP Security Vulnerabilities
</a>
</p>

<p>
According to the reference alert dated November 24, 2026,
Red Hat was expediting the release of security fixes
for the following vulnerabilities:
</p>

<ul>
<li>CVE-2026-115560</li>
<li>CVE-2026-126714</li>
<li>CVE-2026-129289</li>
<li>CVE-2026-129496</li>
<li>CVE-2026-129481</li>
</ul>

<p>
The following vulnerabilities were reported as not
affecting PHP versions shipped in Red Hat Enterprise Linux:
</p>

<ul>
<li>CVE-2026-129182</li>
<li>CVE-2026-129474</li>
</ul>

<p>
For CVE-2026-129291, consult the latest Red Hat
advisory to determine the applicable product status.
</p>

<p style="background:#fff7e6;border-left:4px solid #e65100;padding:12px;">
<strong>Red Hat patch availability:</strong>
The reference alert indicates that fixed Red Hat
packages were not yet available at the time of publication.
Please monitor the official security bulletin for updated
product assessments, RHSA advisories and fixed packages.
</p>

<p>
For distribution-maintained PHP packages, follow the
respective vendor security advisory. Vendors may
backport security fixes without changing the upstream
PHP version number.
</p>

<p style="color:#b42318;font-weight:bold;">
As always, please test security updates before
deploying them to production assets.
</p>

</td>
</tr>

<!-- MITIGATIONS -->
<tr>
<td style="padding:10px 28px;font-size:14px;line-height:1.7;">

<h2 style="font-size:17px;color:#263445;border-bottom:2px solid #e2e8f0;padding-bottom:8px;">
Mitigations
</h2>

<p>
If immediate patching is not possible due to operational
constraints, implement the following temporary
risk-reduction measures where applicable:
</p>

<ul>
<li>Disable persistent FastCGI backend connections.</li>
<li>Do not expose PHP-FPM TCP listeners or Unix sockets directly to untrusted clients.</li>
<li>Restrict PHP-FPM access to localhost, trusted web servers or protected internal networks.</li>
<li>Review NGINX, Apache HTTP Server, HAProxy and LSAPI configurations for backend connection reuse.</li>
<li>Restrict external access to legacy PHP applications wherever possible.</li>
<li>Isolate legacy applications on dedicated hosts or containers to reduce the potential impact of compromise.</li>
<li>Ensure PHP workers and associated services operate with the minimum required privileges.</li>
</ul>

<p style="color:#b42318;font-weight:bold;">
Mitigations are temporary measures and do not replace
installation of the applicable security patches.
</p>

</td>
</tr>

<!-- SPECIFIC WORKAROUNDS -->
<tr>
<td style="padding:10px 28px;font-size:14px;line-height:1.7;">

<h2 style="font-size:17px;color:#263445;border-bottom:2px solid #e2e8f0;padding-bottom:8px;">
Vulnerability-Specific Workarounds
</h2>

<h3 style="font-size:15px;color:#263445;">
CVE-2026-129182 — Fatal-error backtraces
</h3>

<p>
As a temporary workaround, administratively disable
fatal-error backtraces in the affected PHP configuration.
</p>

<table width="100%" cellpadding="12" cellspacing="0" border="0" style="background:#eef2f7;border-left:4px solid #475569;">
<tr>
<td style="font-family:Consolas,monospace;font-size:13px;">
fatal_error_backtraces=0
</td>
</tr>
</table>

<p>
Restart all affected PHP workers and ensure that
request-specific configuration cannot override
or re-enable this setting.
</p>

<h3 style="font-size:15px;color:#263445;">
CVE-2026-129474 — Exception argument handling
</h3>

<p>
Configure affected PHP workers to exclude arguments
from exception stack traces:
</p>

<table width="100%" cellpadding="12" cellspacing="0" border="0" style="background:#eef2f7;border-left:4px solid #475569;">
<tr>
<td style="font-family:Consolas,monospace;font-size:13px;">
zend.exception_ignore_args=1
</td>
</tr>
</table>

<p>
For applicable PHP 8.5 deployments, disabling
fatal-error backtraces is also identified as a
temporary workaround for the reported attack path.
</p>

<table width="100%" cellpadding="12" cellspacing="0" border="0" style="background:#eef2f7;border-left:4px solid #475569;">
<tr>
<td style="font-family:Consolas,monospace;font-size:13px;">
fatal_error_backtraces=0
</td>
</tr>
</table>

<p>
Restart the affected workers and verify the effective
PHP-FPM configuration, including pool-level settings
and application overrides.
</p>

<p>
Changing only the PHP CLI configuration is insufficient
when the vulnerable application uses PHP-FPM.
</p>

<p>
Setting display_errors=0 does not prevent PHP from
constructing backtraces and should not be considered
a complete workaround.
</p>

<h3 style="font-size:15px;color:#263445;">
CVE-2026-129291 — PHP-FPM worker output
</h3>

<p>
Disable worker output capture in affected PHP-FPM
pools as a temporary workaround.
</p>

<table width="100%" cellpadding="12" cellspacing="0" border="0" style="background:#eef2f7;border-left:4px solid #475569;">
<tr>
<td style="font-family:Consolas,monospace;font-size:13px;">
catch_workers_output = no
</td>
</tr>
</table>

<p>
Review the privileges of the PHP-FPM master process.
Running the master without root privileges, where
operationally supported, may reduce the impact of
privilege escalation but does not correct the
underlying use-after-free vulnerability.
</p>

<p>
Disabling cURL or OPcache should not be considered
a complete mitigation.
</p>

<p style="color:#b42318;font-weight:bold;">
Validate all configuration changes in a test
environment before applying them to production.
These workarounds do not replace security updates.
</p>

</td>
</tr>

<!-- REQUIRED ACTIONS -->
<tr>
<td style="padding:12px 28px 24px;font-size:14px;line-height:1.7;">

<h2 style="font-size:17px;color:#263445;border-bottom:2px solid #e2e8f0;padding-bottom:8px;">
Required Actions
</h2>

<p>
Given the potential impact of these vulnerabilities,
we request that all concerned teams and partners
perform an immediate assessment of their perimeter.
</p>

<ol style="padding-left:22px;">
<li>
Identify all PHP installations, including web servers,
PHP-FPM services, containers and bundled PHP runtimes.
</li>

<li>
Determine the installed PHP versions and assess
applicability against the affected release branches.
</li>

<li>
Prioritize Internet-facing applications, business-critical
services and environments processing untrusted input.
</li>

<li>
Upgrade affected installations to the applicable
fixed PHP release or vendor-provided security package.
</li>

<li>
Monitor Red Hat and other distribution-specific
security advisories for updated patch availability.
</li>

<li>
Where immediate patching is not possible, evaluate
and implement the applicable temporary mitigations
and workarounds.
</li>

<li>
Review FastCGI connection reuse, PHP-FPM listener
exposure and worker privileges.
</li>

<li>
Rebuild and redeploy container images containing
affected PHP runtimes.
</li>

<li>
Restart affected PHP workers and verify the effective
runtime version and configuration after remediation.
</li>

<li>
Monitor application and PHP-FPM logs for unexpected
worker crashes, abnormal behavior, unauthorized file
changes or other indicators of potential compromise.
</li>

<li>
Report remediation progress, technical difficulties
and suspected exploitation through the established
security escalation process.
</li>
</ol>

<!-- REMEDIATION REPORTING -->
<h2 style="font-size:17px;color:#263445;border-bottom:2px solid #e2e8f0;padding-bottom:8px;">
Remediation Status Reporting
</h2>

<p>
Please provide an assessment of your exposure and
remediation progress, including the following information:
</p>

<table width="100%" cellpadding="9" cellspacing="0" border="0" style="border-collapse:collapse;font-size:13px;">

<tr style="background:#263445;color:#ffffff;">
<th align="left" style="border:1px solid #cbd5e1;">Information Required</th>
<th align="left" style="border:1px solid #cbd5e1;">Response</th>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">Entity / Company</td>
<td style="border:1px solid #cbd5e1;">To be completed</td>
</tr>

<tr style="background:#f8fafc;">
<td style="border:1px solid #cbd5e1;">Exposure Status</td>
<td style="border:1px solid #cbd5e1;">Affected / Not affected / Under assessment</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">Number of Impacted Assets</td>
<td style="border:1px solid #cbd5e1;">To be completed</td>
</tr>

<tr style="background:#f8fafc;">
<td style="border:1px solid #cbd5e1;">Number of Patched Assets</td>
<td style="border:1px solid #cbd5e1;">To be completed</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">Temporary Mitigations</td>
<td style="border:1px solid #cbd5e1;">Implemented / Not implemented / Not applicable</td>
</tr>

<tr style="background:#f8fafc;">
<td style="border:1px solid #cbd5e1;">Estimated Remediation Date</td>
<td style="border:1px solid #cbd5e1;">To be completed</td>
</tr>

<tr>
<td style="border:1px solid #cbd5e1;">Technical Constraints / Comments</td>
<td style="border:1px solid #cbd5e1;">To be completed</td>
</tr>

</table>

<p>
Please also report any observed attacks, suspicious
activity, technical difficulties or relevant information
that could support the remediation effort.
</p>

<!-- REFERENCES -->
<h2 style="font-size:17px;color:#263445;border-bottom:2px solid #e2e8f0;padding-bottom:8px;">
References
</h2>

<p>
<strong>Official Vendor References</strong>
</p>

<p>
<a href="https://www.php.net/ChangeLog-8.php" style="color:#175cd3;">
PHP — Official PHP 8 Release Changelog
</a>
</p>

<p>
<a href="https://www.php.net/downloads.php" style="color:#175cd3;">
PHP — Official Downloads
</a>
</p>

<p>
<a href="https://access.redhat.com/security/vulnerabilities/RHSB-2026-020" style="color:#175cd3;">
Red Hat — Security Bulletin RHSB-2026-020
</a>
</p>

<p>
<strong>Technical Research and Security Publications</strong>
</p>

<p>
<a href="https://thehackernews.com/2026/11/php-fixes-7-critical-flaws-including.html" style="color:#175cd3;">
The Hacker News — PHP Fixes Seven Critical Vulnerabilities
</a>
</p>

<p>
<a href="https://thehackernews.com/2026/11/phpaftershell-explained-how-hackers.html" style="color:#175cd3;">
The Hacker News — PHPAfterShell Explained
</a>
</p>

<p>
<a href="https://securityaffairs.com/203472/security/php-warns-of-critical-flaws-ahead-of-november-security-release.html" style="color:#175cd3;">
Security Affairs — PHP Critical Vulnerabilities
</a>
</p>

<p>
<a href="https://www.yorku.ca/uit/2026/11/multiple-critical-php-vulnerabilities-phpaftershell/" style="color:#175cd3;">
York University — Multiple Critical PHP Vulnerabilities (PHPAfterShell)
</a>
</p>

<p style="margin-top:28px;">
Best regards,<br>
<strong>Cybersecurity Team</strong>
</p>

</td>
</tr>

<!-- FOOTER -->
<tr>
<td style="background:#202b3a;color:#ffffff;padding:18px 28px;font-size:12px;line-height:1.6;">

<strong>Security Vulnerability Notification</strong><br>

Classification: TLP:AMBER+STRICT<br>

Please handle and distribute this information according
to your organization's information-sharing policy.

</td>
</tr>

</table>
</td>
</tr>
</table>

</body>
</html>
