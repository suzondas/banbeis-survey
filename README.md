# About BANBEIS SURVEY

This is an immense Educational Survey Application that addresses -

- Annually conducted online Education Survey by Bangladesh Government
- Survey Questionnaire for 10 Type of Institutes [School, College, School & College, Technical, Madrasa, University, Professional, Medical, Teachers Training College, English Medium Institutes](http://banbeis.gov.bd/site/forms/a4aee314-4d50-4b0a-b1d2-fbdef9b4eb4f/Annual-Survey-Form-2021-Download) 
- Each Questionnaire contains 10 Pages on an average
- 155 Oracle Tables
- 38 Thousand Users
- 15 Days Data collection Duration
- Performance Optimization Plan for huge traffic
- Security plan for data integrity and different types of attack

## Features
- 4 types of Users (Institute Head, Local Authority, District Authority, BANBEIS) for data collection and acceptance.
- 2 types of Admin Users (Statistics Viewer, Moderator from BANBEIS end)
- Institute Head Adds/Updates information(Infrastructure, Students, Faculty) of Institutes on multiple pages
- There is a validation, cross checking, verification algorithm for successful Submission.
- Then Local Authority verify institutes
- District Authority verifies all institutes in a district
- Finally BANBEIS user verifies all institutes in the country.
- Statistics Viewer enjoys data view using chart, graph and also make reports based on different criteria.
    

## Technologies
- Scripts: Php 7, AngularJs, VueJs
- Host OS: CentOS 
- MVC: Laravel, Lumen
- Sanctum Authentication
- Database: Oracle 11g
- GIT
- NPM, Composer
- IDE: PhpStorm

## Architecture
- MicroService Based
- 3 Servers (Application, API, Database)
- Physical Load Balancing

## Hardware
- Cisco Blade Server
- 128G Ram on Each Server
- 16 Core (3.2ghz) on Each Server
- VMware vSphere with DRS
- Fortinet FortiWeb 400D Application firewall cum Load Balancer

## Contribution
We would like to extend our thanks to the [BANBEIS](http://www.banbeis.gov.bd) for facilitating us to complete this project.  

- [Suzon Das](https://www.linkedin.com/in/suzon-das-2b8112aa/) (Team Lead, Project Manager, Deployer, Code Reviewer )
- Md. Iftiar Alam (UI Designer, Coder)
- Md. Fazlay Rabbi (Schema Builder, Coder)
- Md. Liaz Mahamud Lemon(Co Team Leader,Database Structure Builder, Oracle script writer for data migration and others query,Backend Coder)

## Performance Optimization Plan
Huge Traffic, Short Duration, Limited Bandwidth compelled us to make Performance based Optimization Plan including following four areas:-

##### Hardware Level: 
- We shifted new application to High performing Cisco Blade server and put three tiers of application on three different physical servers.
- Used Physical Load Balancer (weighted round robin algorithm) for for Application server
- Allocating most available resources (Cores, Ram) to the applications

##### Infrastructure Level:
- MicroService Based Architecture
- VMware vSphere DRS for allocating resources on demand
- Different Physical Disc for Oracle DB redo log, log buffer files on NetApp storage Engine
- RAID 10 for DB Storage
- Database's Tables Indexing
- @todo: Apache Multi-Processing Module (MPM) - Worker implementation
- @todo: in Memory Caching Database e.g.-Reddis

##### Framework Level:
- Removing unnecessary NPM, Composer packages, service providers and libraries in Laravel
- Proper Deployment (Caching- Route, config, views; Magnifying resources) with optimization

##### Language Level:
- Fair coding practice with OOP model
- Proper Documentation 
- Usage of reusable functions
- Usage of asynchronous practice in resource fetching 
- Performance based coding with speed consideration
 
## Security
- Sanctum Authentication with added security salt

## Security Vulnerabilities
If you discover a security vulnerability within this Application, please send an e-mail to me via [suzon.du@hotmail.com](mailto:suzon.du@hotmail.com). All security vulnerabilities will be promptly addressed.

## License
- All applications (Oracle 11g, CentOS, IDE-PhpStorm, Windows 10, XAMPP, VMware etc) are either licensed or under open source license. 
- This application is also open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
