Migration Steps Overview:
-------------------------
Migration Strategies (7 R's):

1.) Relocating. &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;5.) Repurchasing

2.) Rehosting   &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 6.) Retaining

3.) Replatfoming&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;7.) Retiring

4.) Refactoring / Rearchitecting
<br><br><br>

**1.) Relocating:** Moving the application already running on a VM to AWS. This is also called Hypervisor lift & shift.

**2.) Rehosting:** This is lift and shift in real sense. We lift the applications running on on-prem infra and start running them on AWS infra.

**3.) Replatforming:** Need to make few optimization with core architecture.

**4.) Refactoring / Rearchitecting:** Refactor the app and introduce cloudnative services to the workflow. This includes containerizing the application.
    Mostly used when converting the monolithic apps to microservices.

--- Remaining 3 strategies are not migration in real sense ---

**5.) Repurchasing:** Moving the purchased licenses to cloud.

**6.) Retaining:** Do nothing to the old apps running on on-prem, but run the new applications/versions on cloud. Slowly retire/phase out the old apps.

**7.) Retire:** Remove the old application running on on-prem, so that they don't add unnecessary cost.

***AWS Prescriptive Guidance:*** https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/introduction.html

