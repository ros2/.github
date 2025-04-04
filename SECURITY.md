# Security Policy

The official security policy is hosted at https://ros.org/reps/rep-2006.html .
The text is reproduced below for convenience.

## Supported Distributions

The list of ROS 2 distributions that receive security updates is at https://docs.ros.org/en/rolling/Releases.html

## Motivation

The developers of the Robot Operating System (ROS) take security very seriously.
As such, we would like to be informed when a security bug is found so that it can be fixed and disclosed as quickly as possible.
The rest of the document outlines what is covered by this policy and how to report security vulnerabilities.

## Scope

The Vulnerability Disclosure Program outlined here covers all code within the ROS 2 Common Packages as defined in REP 2005.

The ROS Security Working Group may also be able to assist you with reporting vulnerabilities which are not in scope of this policy but which are related to ROS or more generally to robotics.
An increasing number of companies are bringing ROS-based products to market, and during this growth period we anticipate vulnerabilities to be identified in products before vendors have an established vulnerability reporting program.
We will work with you on a best-effort basis to help connect you with responsible parties best suited to address your concerns.

## How to submit a vulnerability

Please submit vulnerability reports by emailing security@openrobotics.org, preferably in English.
This is a private list of security officers who can help verify the bug report and develop and release a fix.
The more information provided about the bug, the easier it will be to fix.
If you already have a fix, please include it with your report.
We may ask to exchange PGP keys to discuss sensitive details about the vulnerability which may include proof-of-concept code, an impact assessment, recommended remediation steps or other information that will help us find and fix the problem.

Include any plans you may have to disclose details about the vulnerability.
In order to protect our users, unless otherwise agreed by both parties, we ask that you not publicly discuss the vulnerability until a fix is published or at least 90 days have passed since the initial report submission.
The group handling the report will also follow this timeline.
If you do not wish to be acknowledged in the release communications please indicate so when you submit the vulnerability.

## What to expect in response to a vulnerability disclosure

Expect a timely response to your notification, normally within two business days, during which time we will triage your vulnerability report.

After we have evaluated the vulnerability we will send you our risk assessment and, where applicable, the anticipated time to publish an update.
Where appropriate, we will coordinate and assign a vulnerability ID with an industry-standard.
We will aim at being as transparent as possible about timelines and any issues or challenges which may impact the scheduled fix.

Should the vulnerability have a widespread impact that requires coordinated disclosure, we may, at our discretion, choose to engage a neutral third party such as CERT/CC or ICS-CERT to support coordination efforts.

We will notify you when a pull request has been submitted and approved which remediates the vulnerability.
Because security vulnerabilities can have severe consequences, they differ from other bugs and at our discretion-- in order to protect our users-- we may modify our normal code release processes for publishing open source code updates.

## Safe Harbor

Open Robotics strongly supports security research into ROS software and seeks to encourage that research.
Open Robotics will not engage in legal action against individuals who act in good faith to identify, report and fix vulnerabilities in ROS, so long as they operate in accordance with any applicable laws or this policy.
Research or testing against operating robotic systems without the consent of the owner/operator is in violation of this policy and strongly discouraged due to potential health and human safety concerns.

If at any time you have concerns about whether your activities are consistent with this policy, please contact us at security@openrobotics.org.
