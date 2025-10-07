# netskope-custom-app-connectors
A collection of Netskope Custom Connectors I've built to explore and demonstrate what’s possible. Some are just fun experiments, others are demos to show off how flexible the platform can be in detecting SaaS app activity.

## Usage
1. Download or clone this repo.
2. Login to the Netskope Administrator Portal
3. Go to **Settings > Security Cloud Platform > App Definition > Cloud & Firewall Apps**
4. Click **New App Definition Rule > Cloud App**
5. Click **Import From File > Add to Activity List**
6. Select the activities.json file to import

## Available Custom Connectors
| SaaS App  | Domain(s) | Activity Detection | Notes |
| ------------- | ------------- | ------------- | ------------- |
| Caltopo  | caltopo.com  |Login, Logout, Import, Export, Print, Search, Create, Delete, Share, Update Share, Delete Share| None |
| cPanel  | N/A | Login Successful, Login Failure, Logout |- This connector is specific to the cPanel web hosting administrator portal<br>- Edit the CSV and search and replace *.example.com with your FQDN|
