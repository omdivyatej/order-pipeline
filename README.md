# order-pipeline

Payment/order processing on AWS SQS: reserve stock → charge card → send receipt → update inventory. One queue per step, compensation as its own job, idempotency keys on the charge. Built as a learning project.

**Queue Playbook** (animated walkthrough of the design): https://omdivyatej.github.io/order-pipeline/
