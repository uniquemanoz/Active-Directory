Let Practise In Vmware If You dont Have Separate Server

Once Fresh Installation is done


**Setup Admnistrator Password:** Very Imprtant to set this 
Using Computer Management: System Tools > Local Users and Groups > Users
set password in adminstrator account: H3ll0W0rld!



**Find Server Manager Dashboard**

<img width="1078" height="854" alt="image" src="https://github.com/user-attachments/assets/74ce62ea-d3e1-43cd-b1b9-2160da29032f" />

**Setup Active Directory**
**Find Manage**
1.Add roles and Features
2.Installation :role Based or feature-based installatio****n
3. Select server from server pool and select **lsited server** below
4. select **active directory domain services** , **Group Policy Management** and then click at **add features**
5. You can more features like Hyper-V, DNS Server, Remote Acces, Remote  Desktop Services
5. do next
6. Once installation is finsihed
7. setup up promote this server to domain Controller

<img width="522" height="196" alt="image" src="https://github.com/user-attachments/assets/41fac6c5-4759-45a2-8c32-65755a746d56" />

8. Deployment Configuration once clicked at promote this server to domain Controller
9. Add forest...myoffice.local
10. select most recent sever at forest functional level:
11. Tick DNS server
12. Tick Global Catalog
13. Password: H3ll0W0rld!
14. you will see NetBIOS domain name: MYOFFICE
15.  Reboot

**Active Directory Users and Computer**

Organisation Unit (OU)
> Domain, Computers, USer, Group,Conatainer, PrintQue,Contatc,...

myoffice.local
>> add OU as Austrlia
>> Can make Group like IT, Management...there are group security as well

>> Group
>> Group Type
>Built In Security Group
>> Custom Security Groups
>> Assign Permission (Full Control, read, modify)


Create User:
Full Name: Manoj Pokharel
user logon name: manojpokharel@myoffice.local
pasword: H3ll0M@n0z


** Creating and Setting up Group Policy Object (GPO)**
GPMC Group Polcy Management
>> Add new policy as Password Policu
>> right click and edit
>> you will see computer congigurations and user configuration

