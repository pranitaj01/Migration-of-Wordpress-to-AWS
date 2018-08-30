# Project Title

Migration of Wordpress Website to AWS

## Getting Started

  I use WordPress.com for writing blogs. I would like to launch a website of my own using AWS services and run and manage my WordPress content through them.
  This project highlights majorly on the objective of migrating my entire WordPress website content on AWS platform. This project will let you exploit the AWS services as per your requirement with much simplicity and ease.

### Prerequisites

- Basic understanding of AWS concepts.
- Access to AWS free tier management console.
- A registered domain name.
    Specifically for this project, your domain name is the one you use for your current WordPress website.
```
pranita91.com is my domain name I used for this project.
The same domain is now downgraded to pranita91.wordpress.com (N/A for this project)
```
- Sense of curiosity will help you explore and research more around this project


### Basic Installation/Software/Accounts

- Create an AWS free tier account (If you don't have on already)

```
https://aws.amazon.com/free/
```

- Create a WordPress website. Add any content like images/blogs etc
    In this project, I am using my already existing WordPress.com website with blogs written in it.
```
https://wordpress.com/
```
OR
```
https://wordpress.org/download/
```


### Procedure

The procedure is divided into three steps:
- Deploy WordPress installation
    Launch a WordPress installation on Amazon AWS virtual machine using AWS EC2 service.
- Transfer Domain name
    Transfer/point your existing domain name to new WordPress isntallation on AWS using AWS Route53 service.
- Import WordPress website content
    Migrate/Transfer/import existing WordPress website content to new WordPress installation on AWS using inbuilt tools/plugins.
    
 To follow each step in detail, use the following document:
```
 Migration-of-Wordpress-to-AWS/Wordpress project.docx 
```

### Project Costs
- Total cost of this project: $0.51.

- If using WordPress.com, a Free plan will not allow to do domain/plugins settings. Check other updgrades here:
```
 https://en.support.wordpress.com/plan-features/ 
```
Hence WordPress.org is recommended.

- In AWS free tier check pricing for hosted zone
```
 https://aws.amazon.com/route53/pricing/ 
```

## References
- https://aws.amazon.com/getting-started/tutorials/launch-a-WordPress-website/
- https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html
- https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html
- WordPress.com to WordPress.org migration
  https://www.elegantthemes.com/blog/resources/migrating-wordpress-com-to-wordpress-org-a-step-by-step-guide
- About Plugin:
  https://wordpress.org/plugins/all-in-one-wp-migration/
- Other widely available resources/knowledge on the internet

## Questions
Q) Why I am not able to add/install plugin on WordPress.com?
A) You cannot do it if you are using WordPress.com and you have a Free plan active on it, or your domain name look like - "pranita91.wordpress.com". 
Solutions -
  Refer below document to do the import/export without plugin. Howver, plugin use is recommended to import/export extensive web content.
  ```
  Migration-of-Wordpress-to-AWS/Wordpress project.docx 
  ```
OR
  upgrade your WordPress.com plan to Business Plan (They offer refund too. Check WordPress.com refund policies.
  ```
    https://en.support.wordpress.com/refunds/ 
  ```
OR
  Use Wordpress.org account. Wordpress.org will not pose any restricitons on domain/plugins settings. 
  ```
  https://wordpress.org/download/
  ```
  You can also migrate your WordPress.com to WordPress.org for free
  ```
  https://www.elegantthemes.com/blog/resources/migrating-wordpress-com-to-wordpress-org-a-step-by-step-guide
  ```

Q) Why I cannot do any change to my domain settings. Why cannot I customize my name servers to direct my website to new host?
A) If you have account with Free plan on WordPress.com, WordPress.com will only have access to your domain settings or name server settings. Hence, I upgraded my plan to Personal, thereby allowing me to change Name Server settings.
OR
Use Wordpress.org account. Wordpress.org will not pose any restricitons on domain/plugins settings. 
```
https://wordpress.org/download/
```
You can also migrate your WordPress.com to WordPress.org for free
```
https://www.elegantthemes.com/blog/resources/migrating-wordpress-com-to-wordpress-org-a-step-by-step-guide
```
