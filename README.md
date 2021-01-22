# WebFormExample
# JSONPowerDB


JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database.

Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.

Whether it's a Dynamic Website or a Mobile App or some Data Analytics Portal, the development is real fun and fast. Nothing better than trying it yourself. What all you need is a basic understanding of HTML, CSS, Bootstrap, and Javascript.

Note: Using JsonPowerDB is equally Easy and Fast when used with Server Side programming like Java, .NET, Python or PHP etc.

# Use Cases
# All Dynamic web applications.


All Mobile applications that require backend database.
Session Caching.
Page Caching.
Existing Database applications to improve their reporting / analytics performance.
Best suited as backend Database for IoT.
Live HTML templates / themes.
Any software application that needs backend database.

# Products
To suit every application’s backend database requirements.

Shared JPDB - free / low cost DBSaaS: Click here to register now.

Downloadable and freemium JPDB instance: Click here to download.

Dedicated JPDB instances: Contact Us

Customized JPDB as per requirement: Contact Us


# Features
JsonPowerDB (JPDB) is Next Generation, Creative and Disruptive Multi-mode DBMS_ with many USPs.

Proprietary algorithm for High Performance CRUD operations. Multiple times faster than popular DBMS.

Serverless support for faster development - A UI developer can develop complete dynamic application.

DBMS with built in web / application server and embedded caching makes the performance lightning fast.

Server side Native NoSQL - best query performance.

In-built support to query on multiple JPDB databases.

Multi-mode DBMS - Document DB, Key-Value DB, RDBMS support.

Schema free - easy to develop and maintain.

Web-services API - Can be used with any programming language that has support for HTTP.

Multiple security layers.

Nimble, Simple to use, In Memory, Real-time DBMS.


# Release Notes
# v0.3.2.20190205.1721 beta
0.3.2 / 2019-02-05
==================

 * Added: New implementation of Small Token for newly generated connection token.
    - Using Small-token, KVPDB request size will be reduced.
    - Fast Execution of KVPDB operation.
 * Added: JPDB Help in UI of User Dashboard, Now User can directly go to JPDB Help Docs for any API help. 
 * Improved: User can now add the description of the connection-token, in which application user is using connection-token,
    - Easy To understand which connection-token is used where.
 * Improved: Limit Functionality in JsonPower SQL Query.
 * Improved: UI of Company User Management Webpage in Company Dashboard and User Tools Webpage in User Dashboard.
 * Changed: User SMTP settings Webpage moved to User Tools Webpage.
 * Fixed: Important bugs.
 
# v0.3.2.20181127 beta
 0.3.2 / 2018-11-27
==================

 * Added: New implementation of JsonPower SQL Query using HTTP REST API.
    - User can now query their data using JsonPower SQL Query which is,
    - Easy To understand.
    - Fast.
 * Added: Added support to generate a new connection-token.
    - To use it directly in any application to access JPDB IML, IRL, IDL, ISL and serverless api.
    - Increase security of data as user does not need to provide his user-id and password. 
 * Added: Added support for creating new column in UPDATE command.
 * Added: Added support to get workspace name and workpspace ID of a given workspace in key-value DB.
 * Added: Added support to set or change the time limit for user-token.
 * Improved: Improved the performance of Backup, PUT and PUTALL command, Commit and Recovery.
 * Changed: UI of "User Tools" & "Company-Settings".
 * Fixed: Important bugs.
                         
#  v0.3.2.20181004 beta
0.3.2 / 2018-10-04
==================

 * Added: New implementation of Key-Value data structures and supported HTTP REST API.
    - Multiple data structure in one Workspace.
        - Each Workspace will have one default data structure and multiple 'named' HashMap data structures.
        - All Workspace allows key-value pair data to be stored.
        - Expire of individual key-value pair can be configured through API.
    - Multiple Workspace can exist in Workspace_Pool.
    - Separate API for default data structure and HashMap data structures.
 * Added: Backup, Download, Upload, Restore and Delete JPDB backups.
 * Added: Commit and Recovery with User level controls only if organization / company admin allow.
 * Added: Added support for creating the structure of relation without inserting any data.
 * Added: Added favicon on all dashboard and in Help documentation.
 * Changed: API improved for serverless features.
 * Fixed: Important bugs.    
 
# v0.3.2.20180615 beta
0.3.2 / 2018-06-15
==================

 * Added: Help / Documentation site is created. Check http://login2explore.com/jpdb/
  - jpdb-common-reference.js: Helper jar Java developers to easy use of JPDB API from java. 
  - CRUD examples added for JPDB user / developers. 
  - API reference 
  - NoSQL reference (2018-06-22)
  - NoSQL examples (2018-06-22)
 * Added: Added support for automatic indexing of new Columns in request.
 * Added: New command API added for 'IS_COLUMN_INDEXED' and 'IS_COLUMN_EXIST'.
 * Added: Limits data size per user in request and response for a specfied duration. 
 * Added: Auto registration of new user in help / support email lists.
 * Added: JPDBUtils.jar: Helper jar Java developers to easy use of JPDB API from java. 
 * Added: Added basic infrastructure for JPDB installations monitoring through JSSM server.
 * Fixed: Various Bug fixes and improvements.

# v0.3.2.20180507 beta
0.3.2 / 2018-05-07
==================

 * Added: Security Layers for API access
 * Added: Serverless support for client’s session management
 * Added: Serverless support of SMTP Settings for user for sending emails
 * Added: Support for System properties like database access limits or restrictions, and status related controls, JPDB and JSSM host details
 * Added: Support for company to create and modify email template for sending emails
 * Added: Java utility class JPDBUtils.java to help developers to ease development 
 * Added: Release version is now displayed on user and company dashboard
 * Changed: Display warning message on Company Dashboard, if SMTP is not set
 * Changed: UI of "Add Index" & 'Unindex Column" 
 * Fixed: Heartbeat interval
 * Fixed: JSSM status admin removed in user management table of JPDB Company
 * Fixed: Same JPDB instance can now be both JPDB and JSSM
 * Fixed: After User licence limit exceed, a warning message displayed to user who is trying to register
 * Fixed: Ambiguity of intallation id resolved
 * Fixed: After adding 5 user, if SMTP of company is not set new user will not be able to login to JPDB user dashboard 
           
  
#  v0.2.7.20170919 alpha
0.2.7 / 2017-09-19
==================

 * Added: Developer dashboard more easy to use, by which developer can insert, remove, update records easily
 * Added: NoSQL, using this feature developer can write their own query script in native (java) language and execute that script on JsonPowerDB server 
 * Added: NoSQL is designed using QueryService interface which contains some ready to use high performance, easy to use query support methods
 * Added: NoSQL also has support for passing parameters to the QueryService interface’s execute methods
 * Added: User can add new index and remove existing index into/from JsonPowerDB
 * Fixed: Restricted indexing on Boolean columns
 * Fixed: Method which give accurate file size by deducting deleted record count
  
# v0.2.5.20170810 alpha
0.2.5 / 2017-08-10
==================

 * Added: Any Json row if inserted by default it will store in JsonPowerDB
 * Added: User have facility to remove database
 * Added: User can add new index or column in JsonPowerDB
 * Added: User can remove single column in JsonPowerDB
 * Fixed: If Column is not added(indexed) in PowerIndex then Error Message returned to the Client
 
# v0.2.5.20170718 alpha
0.2.5 / 20170718
================
 
 * DBaaS - A Database SAAS: Available as shared environment or as independent server on Internet / Intranet / Extranet / Cloud.
 * A Single Instance - Million Indexes: Can support over a million indexed columns in a single instance spread across users and databases.
 * Querying Multiple Databases: Allows querying multiple databases which is as simple and fast as querying on single database.
 * Serverless Architecture Support: Minimum learning curves, builds faster, cuts time to market, reduces the development cost.
 * NoSQL: Native Server Side NoSQL, suitable for high performance real-time data processing.
 * REST-API Webservice: Schema-free, Simple to use, Nimble and In-Memory database.
 * Developer - Dashboard: Helps developers in faster coding, in-turn reduces development cost.
 * PowerIndeX Energized: JsonPowerDB is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
                                    
