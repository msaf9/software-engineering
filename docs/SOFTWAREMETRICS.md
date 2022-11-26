<h1> Examples of Software Metrics </h1>

<!-- - [Introduction](#introduction)
- [Agile process metrics](#agile-process-metrics)
- [Lead time](#lead-time)
- [Cycle time](#cycle-time)
- [Team velocity](#team-velocity)
- [Open/close rates](#openclose-rates)
- [Production](#production)
- [Active days](#active-days)
- [Assignment scope](#assignment-scope)
- [Efficiency](#efficiency)
- [Code churn](#code-churn)
- [Impact](#impact)
- [Mean time between failures (MTBF) and mean time to recover/repair (MTTR)](#mean-time-between-failures-mtbf-and-mean-time-to-recoverrepair-mttr)
- [Application crash rate (ACR)](#application-crash-rate-acr)
- [Security metrics](#security-metrics)
- [Endpoint incidents](#endpoint-incidents)
- [Mean time to repair (MTTR)](#mean-time-to-repair-mttr)
- [Size-oriented metrics](#size-oriented-metrics)
- [Function-oriented metrics](#function-oriented-metrics)
- [Errors per FP or Defects per FP](#errors-per-fp-or-defects-per-fp)
- [Defect Removal Efficiency (DRE)](#defect-removal-efficiency-dre)
- [References](#references) -->

## Introduction

<p>There is no standard or definition of software metrics that have value to software development teams. And software metrics have different value to different teams. It depends on what are the goals for the software development teams.</p>

## Agile process metrics

Agile process metrics focus on how agile teams make decisions and plan. These metrics do not describe the software, but they can be used to improve the software development process.

## Lead time

Lead time quantifies how long it takes for ideas to be developed and delivered as software. Lowering lead time is a way to improve how responsive software developers are to customers.

## Cycle time

Cycle time describes how long it takes to change the software system and implement that change in production.

## Team velocity

Team velocity measures how many software units a team completes in an iteration or sprint. This is an internal metric that should not be used to compare software development teams. The definition of deliverables changes for individual software development teams over time and the definitions are different for different teams.

## Open/close rates

Open/close rates are calculated by tracking production issues reported in a specific time period. It is important to pay attention to how this software metric trends.

## Production

Production metrics attempt to measure how much work is done and determine the efficiency of software development teams. The software metrics that use speed as a factor are important to managers who want software delivered as fast as possible.

## Active days

Active days is a measure of how much time a software developer contributes code to the software development project. This does not include planning and administrative tasks. The purpose of this software metric is to assess the hidden costs of interruptions.

## Assignment scope

Assignment scope is the amount of code that a programmer can maintain and support in a year. This software metric can be used to plan how many people are needed to support a software system and compare teams.

## Efficiency

Efficiency attempts to measure the amount of productive code contributed by a software developer. The amount of churn shows the lack of productive code. Thus a software developer with a low churn could have highly efficient code.

## Code churn

Code churn represents the number of lines of code that were modified, added or deleted in a specified period of time. If code churn increases, then it could be a sign that the software development project needs attention.

## Impact

Impact measures the effect of any code change on the software development project. A code change that affects multiple files could have more impact than a code change affecting a single file.

## Mean time between failures (MTBF) and mean time to recover/repair (MTTR)

Both metrics measure how the software performs in the production environment. Since software failures are almost unavoidable, these software metrics attempt to quantify how well the software recovers and preserves data.

## Application crash rate (ACR)

Application crash rate is calculated by dividing how many times an application fails (F) by how many times it is used (U).

        ACR = F/U

## Security metrics

Security metrics reflect a measure of software quality. These metrics need to be tracked over time to show how software development teams are developing security responses.

## Endpoint incidents

Endpoint incidents are how many devices have been infected by a virus in a given period of time.

## Mean time to repair (MTTR)

Mean time to repair in this context measures the time from the security breach discovery to when a working remedy is deployed.

## Size-oriented metrics

Size-oriented metrics focus on the size of the software and are usually expressed as kilo lines of code (KLOC). It is a fairly easy software metric to collect once decisions are made about what constitutes a line of code. Unfortunately, it is not useful for comparing software projects written in different languages. Some examples include:

- Errors per KLOC
- Defects per KLOC
- Cost per KLOC

## Function-oriented metrics

Function-oriented metrics focus on how much functionality software offers. But functionality cannot be measured directly. So function-oriented software metrics rely on calculating the function point (FP) — a unit of measurement that quantifies the business functionality provided by the product. Function points are also useful for comparing software projects written in different languages.

Function points are not an easy concept to master and methods vary. This is why many software development managers and teams skip function points altogether. They do not perceive function points as worth the time.

## Errors per FP or Defects per FP

These software metrics are used as indicators of an information system’s quality. Software development teams can use these software metrics to reduce miscommunications and introduce new control measures.

## Defect Removal Efficiency (DRE)

The Defect Removal Efficiency is used to quantify how many defects were found by the end user after product delivery (D) in relation to the errors found before product delivery (E). The formula is:

        DRE = E / (E+D)

The closer to 1 DRE is, the fewer defects found after product delivery.

With dozens of potential software metrics to track, it’s crucial for development teams to evaluate their needs and select metrics that are aligned with business goals, relevant to the project, and represent valid measures of progress. Monitoring the right metrics (as opposed to not monitoring metrics at all or monitoring metrics that don’t really matter) can mean the difference between a highly efficient, productive team and a floundering one. The same is true of software testing: using the right tests to evaluate the right features and functions is the key to success. (Check out our guide on software testing to learn more about the various testing types.)

## References

- [Stackify](https://stackify.com/track-software-metrics/)
