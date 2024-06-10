# ⓫ Chaos testing: JWT Pizza

We have built in to the JWT Pizza application the ability to inject Chaos into the system. It is an important part of your role as a DevOps engineer to know how to efficiently respond to critical events. This deliverable will give you significant experience with the process.

## ☑ Assignment

You job is to do the following:

1. Make sure the application is up and running correctly during the testing period. This will be announced previous to it beginning.
1. Have all the [metrics](../grafanaMetrics/grafanaMetrics.md) and [logging](../grafanaLogging/grafanaLogging.md) reporting in place necessary for you to be able to observe and diagnose the failure.
1. Have an appropriate [altering system](../grafanaOnCall/grafanaOnCall.md) in place so that you are effectively on call during the entire testing period.
1. Respond to the incident in a timely manner.
1. Properly diagnose the the root cause of the failure.
1. Propose and deploy a remedy.
1. Produce an [incident report](../incidentReport/incidentReport.md) using the template found in the `jwt-pizza` repository under the [incidentReports](https://github.com/devops329/jwt-pizza/tree/main/incidentReports) folder.

⚠️ **Note**: that multiple incidents may occur during the testing period. You will need to respond immediately to all of them. If you are unable to be on call during the defined testing period you have the responsibility to notify the instructor and negotiate an alternative schedule.

As you resolve the incidents and generate your report you must commit the report to your fork of the `jwt-pizza` repository in a folder named `incidentReports`.The report filename should follow the convention `incident-YYYY-MM-DD-#.md`. For example:

```txt
incidentReports/
├── incident-2025-03-01.1.md
└── incident-2025-03-01.2.md
```

After the testing period has ended, submit the URL for the location of where the incident reports are found in your fork of the `jwt-pizza` repository to the Canvas assignment. This should look something like this:

```txt
https://github.com/youraccountname/jwt-pizza/tree/main/incidentReports
```

### Rubric

| Percent | Item                                                                                                       |
| ------- | ---------------------------------------------------------------------------------------------------------- |
| 80%     | Timely response and correction to chaos incidents. 5% is deducted for each hour that the failure persists. |
| 20%     | Accurate and informative incident reports                                                                  |