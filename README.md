📨 MQ and Database Integration in IBM App Connect Enterprise
This repository contains a fully implemented IBM App Connect Enterprise (ACE) solution that processes messages from IBM MQ, transforms them using Graphical Data Mapping, and stores the result in IBM DB2. It supports COBOL and XML message formats via data models defined in a shared library and uses external policy definitions for JDBC database connectivity.

📂 Project Structure
.
├── RouteComplaint/            # Main application with message flow and library references
│
├── ComplaintDataModels/       # Shared library with DFDL schema generated from COBOL Copybook and XML schema model
│
├── DB_DATA_PROJECT/           # Database definition for use in DB node
│
└── DefaultPolicies/           # Policy project for JDBC connection configuration
