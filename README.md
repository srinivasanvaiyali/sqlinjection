# sqlinjection
Exploiting SQL Injection vulnerability

# AIM:
To exploit SQL Injection vulnerability using Multidae web application in Metasploitable2

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

SQL Injection is a sort of infusion assault that makes it conceivable to execute malicious SQL statements. These statements control a database server behind a web application. Assailants can utilize SQL Injection vulnerabilities to sidestep application safety efforts. They can circumvent authentication and authorization of a page or web application and recover the content of the whole SQL database. Identify IP address using ifconfig in Metasploitable2


![image](https://github.com/srinivasanvaiyali/sqlinjection/assets/145117665/8b85f624-5c11-4b48-a1dd-973dacd93824)


Use the above ip address to access the apache webserver of Metasploitable2 from kali linux. In Kali Linux use the ip address in a web browser.

![image](https://github.com/srinivasanvaiyali/sqlinjection/assets/145117665/418b6000-f48f-497c-ab8e-7813c1c332d6)

Select Multidae from the menu listed as shown above. You will get the page as displayed below:

![image](https://github.com/srinivasanvaiyali/sqlinjection/assets/145117665/8210dc99-4801-4d65-9a44-16c39baf007d)

Click on the menu Login/Register and register for an account


![image](https://github.com/srinivasanvaiyali/sqlinjection/assets/145117665/82f11855-7bef-4e76-840c-cad6d0464234)

Click on the link “Please register here”

![WhatsApp Image 2024-05-10 at 12 50 58 PM (1)](https://github.com/srinivasanvaiyali/sqlinjection/assets/145117665/56dbfddd-5ba6-4034-b26c-c5315b25c7a6)

Click on “Create Account” to display the following page:

![image](https://github.com/srinivasanvaiyali/sqlinjection/assets/145117665/401fb039-5499-4b64-962e-7e5a91d4fea4)

## RESULT:
The SQL Injection vulnerability is successfully exploited using the Multidae web application in Metasploitable2.
