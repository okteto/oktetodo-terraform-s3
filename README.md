# Oktetodo

A todo list application showing how you can provision external resources (like an AWS S3 bucket in this case) your application might need with Okteto using Terraform.

## Steps to Run it

1. Create the following [Okteto secrets](https://www.okteto.com/docs/cloud/secrets/) with your AWS account values.
```
AWS_ACCESS_KEY_ID
AWS_REGION
AWS_SECRET_ACCESS_KEY
```

Note: Make sure this user has the permissions to create S3 buckets.

2. Deploy the application from the UI using the Git URL (https://github.com/okteto/oktetodo-terraform-s3) option or clone the repo and run `okteto deploy` or `okteto up`.

3. [Slides](https://www.okteto.com/videos/unifying-dev-and-prod-environments-with-terraform-and-okteto-a-must-for-every-platform-engineer/?_hsmi=279713192&_hsenc=p2ANqtz-_v7on6blDegv_s93-shwqiKxlLpAirFBENz9OPldmiXSlLtztM3wllGuXRTl9VABOrFk2AlX8f0LsfebEFwcd9CzLT2g)
4. [Recording](https://cfq6x04.na1.hubspotlinks.com/Ctc/T+113/cFq6X04/VWWWW0643MwXW1XJ0TR12PmwjW3S9mTt551vDfN7lCf0P2_3wgW95jsWP6lZ3pdW2RqmKx8q7tgDW6_TnLB8qTmT-W3BrX9c5vsvd8W6s5zwY8B076nMZMq6MGMFGYW8s3jFb5nwzL5VxNsDt8_LM_JW1w-Kj58jwXBmW1N0FCx6j0XrrW1K8t2K24JYybW2-pjy04lDnd8W1PtkcQ2X23YMW1GFRdd8X2wghW2ct5q364L_P4F7KtKNMj-7HW43c8Pj7f7VZqW3Wx5x42gkn86W6LZPzK5B4DkNW59JHvK1bzrJrW1kS4411k6-k_W5X4rR61cZPfrN7Yq_6z1vhdWVYgg0F7tfxJ5W1SGHlj266D9LVc_4Y38L0scCN2j_JM9bYZKZW3gtFx87VXCnBW75KY413Pwwj0N47CLRkdjb3wW7g34j8883fmYf8lr74H04) 
