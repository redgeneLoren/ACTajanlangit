# Authentication

### Role Assignment

In using the application requires you to log in using the URL: `http://actajanlangit.herokuapp.com` with the following credentials needed:

- Email address

- Password

 The `credentials` are created by the assigned `admin` base on `role assignment`. 

 The Role assignment is divided into two criterias: `Admin Role` and `Non-Admin Role`. In each different roles have different access to the features of the application. 

 However, one `user` can have multiple roles in the application.

<ins>`Admin Role`</ins>

- The `admin role` is also referred to as the `super admin`. The `super admin` have access to all features of the application. The super admin is also in charge with the registration of users to access the application.

- In the User Authentication feature the `admin role` also known as `super admin` they have access to the following:

    `Super Admin Features - User Authentication Feature`
        
    - Create Users
    - View list of Users
    - Assign role for users.
    - Assign permission to users.
    - Suspend users.
    - View list of suspended users.
    - Edit user details
    - View user details
    - Change credentials/password of users.

<ins>`Non-Admin Role`</ins>

- The `non-admin` role is referred to as the `user` they have limited access to the feature of the application.

- In User Authentication feature the `non-admin` also known as `user` have access to the following:

    `Non-Admin (user) - User Authentication Feature`

    - View their personal profile
    - Update their personal profile

<strong>`Role Assignment Features`</strong>

There are different `job roles` in using the application. These job roles are called `role assignment per feature` to the system. Below are the different `role assignment per feature`.

1. `Cost Engineer` - The role of the `cost engineer` is to estimate the cost of projects, analyze requirements and specification of a project and determine the cost involved to execute such project. In the `AC Tajanlangit system` the role assignment feature of a `Cost Engineer` are as follows:
    
    - View details of material scopes and schedules
    - Create material items schedules
    - Submit material items schedules for approval
    - Create job Order
    - Create billing for accounting
    - View gantt chart

2. `Planner` - The role of a `planner` is to develop a plan to complete a project based on budget, work schedule and available resources. In the `AC Tajanlangit system` the role assignment feature of a `Planner` are as follows:

    - Submit material scopes and schedules for approval
    - Upload material scopes and schedules 

3. `Purchasing Officer` - The role of a `Purchasing officer` is to research on potential vendors, compare and evaluate offers from suppliers and negotiate contract terms of agreement and pricing. In the `AC Tajanlangit system` the role assignment feature of a `Purchasing Officer` are as follows:

    - Submit purchase request for approval 
    - Create purchase orders from purchase request
    - Create service purchase order from job order
    - View list of all purchase orders
    - View list of all service purchase orders
    - Edit purchase order
    - View list of purchase requests
    - Edit purchase request

4. `Warehouse Man` - The role of `Warehouse man` is to receive and process incoming stocks and materials, picking and filing orders from stock, packing and shipping orders and managing stock in the warehouse. In the `AC Tajanlangit system` the role assignment feature of a `Warehouse man` are as follows: 

    - View list of approved and incoming purchase orders
    - Check and note received items from purchase order document.

5. `Accounting` - The role of `Accounting` is responsible for the general ledger, job cost, bank reconciliations and accounts payable. In the `AC Tajanlangit system` the role assignment feature of the `Accounting` are as follows:

    - View list of purchase orders
    - View details of a service purchase order
    - Mark service purchase order as completed
    - View list of purchase orders 
    - View details of a purchase order
    - Mark purchase order as completed
    - View list of billings
    - View details of billings
    - Confirm billings from Cost Engineer
    - Leave remarks to Service Purchase orders
    - Leave remarks to Billings

6. `Project Manager`

    - Request approval for changes of activity duration, start and finish
    - Ability to check purchase request
    - List of purchase requests
    - View details of purchase request
