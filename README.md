<b>Installation</b>

Download the 'schema' and 'ppcm' zip files and install them in this order:
1. 'schema' plugin
2. 'ppcm' plugin

<b>Recommendation</b>

1. Create a new security group and corresponding role in your PowerSchool instance (ie Contact Manager)
2. Assign this role to users in your district who will review the PPCM Dashboard.  These users will review, approve, and/or deny all requests. 
3. After installation, edit the link below with your PowerSchool district subdomain (the red part) below to access your PPCM prefs page.

https://{yourschooldistrict}.powerschool.com/admin/ppcm/prefs.html<br><p>
![image](https://github.com/user-attachments/assets/9dda1dfd-f112-46dc-86f4-c71d5de10780)

<b>Functionality Tiers</b>

<b>View Only</b>
<ul>Upon successful installation, this plugin will immediately display a new 'Contact Management' page (located in the left menu of the Parent Portal).</ul>

<b>Contact Management</b>
<ul>To allow a parent/contact to edit existing and submit additional contacts:</ul>
<ol>
  <li>Select a student record and navigate to Student Profile > Contact Management</li>
  <li>Identify the parent/contact and click the 'edit pencil' icon in the Actions column in the far right column of the contact table</li>
  <li>Check the parameter box for 'Manage Contacts' (this is a per student setting)</li>
</ol>

<b>Additional Security Consideration</b>

Follow these steps to limit administrative rights for setting a contact's ability to 'Manage Contacts' (must have PS admin rights to set Field Level Security)
1. Navigate to https://{yourschooldistrict}.powerschool.com/admin/fieldlevelsecurity/getFieldLevelSecurityTableData.action
2. Choose 'Add' in the top right
3. Choose the 'U_SCD_X' data table
4. Choose the 'MANAGECONTACTS' field
5. Find this newly added field in the Field Level Security table.
6. Set your desired security groups/permissions accordingly.
