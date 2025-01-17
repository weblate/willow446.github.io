---
title: "Faq"
date: 2023-07-10T12:14:12-04:00
---

<div class="faq-wrapper">
<div class="faq-center">
{{% markdown %}}

# Frequently Asked Questions

<div class="faq-subsection">
{{% markdown %}}

## Getting Started

<details>
<summary>
What is a repository?
</summary>
{{% markdown %}}
A _**repository**_ is simply a place where you can store and share your files and folders securely, using **Ouisync**. You can think of it as a root folder, or even a safe, that will contain other folders and files that you want to share with your peers.
{{% /markdown %}}
</details> 

<details>
<summary>
Where can I see my repositories?
</summary>
{{% markdown %}}
When you open the **Ouisync app**, after the onboarding screens you will see the main screen listing all the repositories you have created. Initially this screen will be empty, but as you begin creating _**repositories**_, they will be listed here. 

{{< figure src="/img/my_repositories.png" alt="Ouisync home page listing your repositories">}}

{{% /markdown %}}
</details> 
<details>
<summary>
How can I create new repositories?
</summary>
{{% markdown %}}
To create a new _**repository**_, tap the  **+** button: {{< figure src="/img/plus_button.png" alt="Tap the Plus button" >}}
  
Then select **"Create Repository"**:
{{< figure src="/img/create_repository.png" alt="Select 'Create repository'" >}}

...and give it a name:

{{< figure src="/img/name_repository.png" alt="Give your repository a nice name." >}}

You also have the option here to protect your repository with a local password or your biometrics (if you've got them set up on your device).

#### See [**_What is a 'local password'?_**](https://github.com/equalitie/ouisync-app/wiki/_new#what-is-a-local-password) to learn more about them.

{{% /markdown %}}
</details> 

<details>
<summary>
Do I have to set up a password (or biometrics) to protect my repositories?
</summary>
{{% markdown %}}
There is no requirement to protect your repositories either by password or by biometrics. Whether you decide to do it depends on the sensitivity of data that you store in Ouisync repositories and habitual usage of your devices.  For storing and sharing photos of your cat, maybe a password is not necessary.  But for storing more sensitive personal data, we recommend passwords (or biometrics) be set up.

To do that, tap on Add local password: 

{{< figure src="/img/create_local_password.png" alt="Adding a local password" >}}

After that you will see this dialog box and you can either set up a local password or select the biometrics protection (if you have it set up on your device):

{{< figure src="/img/set_password.png" alt="Setting a local password or biometrics authentication" >}}

You can have a different password for each repository.  It is also possible to have a mixture of password (or biometrics) protected Ouisync repositories and ones without protection. 

If you do not set up the password or biometric protection when creating a repository, you can do it later by going to the Repository settings (the three vertical dots next to the repository name) and to the Security options for that repository.

{{< figure src="/img/security_options.png" alt="Change repository security options in Settings" >}}

{{% /markdown %}}
</details>

<details>
<summary>
Why is it called 'local password' and not simply 'password'?
</summary>
{{% markdown %}}
A local password is a password set up only for your own device. You don't need to share it with your peers. They can set up their own passwords to protect the shared **Ouisync** _**repositories**_ on their own devices.
{{% /markdown %}}
</details>

<details>
<summary>
How can I add files and folders to my repository?
</summary>
{{% markdown %}}
That's easy. Tap on the repository name.  This will take you to the _**repository**_ contents screen where you will see a Plus button: {{< figure src="/img/plus_button.png" alt="Tap the Plus button" >}}

This will open a small window where you can choose whether to create a folder for your files within that repository or add files to it from your device or external storage (such as a USB stick or SD card):   
{{< figure src="/img/add_folder_files.png" alt="Add folders or files" >}}

There you can decide to create a new folder: 
{{< figure src="/img/create_folder.png" alt="Create a new folder" >}}

Or you can import files into one of the existing folders. 
{{% /markdown %}}
</details> 

<details>
<summary>
What does it mean to 'import' a repository?
</summary>
{{% markdown %}}
To import a _**repository**_ means that you want to recreate on your device a _**repository**_ that a peer has shared with you.  

You start with the same **+** button and then select **'Import'**:
{{< figure src="/img/import_repo.png" alt="Select to import a repository" >}}

Tapping on the **Import repository** button will bring you to this screen:
{{< figure src="/img/import_repo2.png" alt="Select to import a repository" >}}

Here you have two options - you can scan a QR code generated by your peer or import a link your peer has sent you (by email, any messaging app etc). ​The link looks like this:
{{< figure src="/img/import_link.png" alt="Shared repository link" >}}

After you copy and paste the link you received from your peers into the provided field, or after you scan the QR code of the repository you wish to import, the imported repository will appear on your screen and after a short while all its content will be imported into your device.  You now have on your device a replica of the repository that your peer shared with you.   
{{% /markdown %}}
</details>

<details>
<summary>
How can I use my repository as a secure backup?
</summary>
{{% markdown %}}

### Create Secure Backups

You can create a secure backup repository on a spare device of your own or even on a friend's device. To do that you first need to generate the **Write** token link for the _**repository**_ that you want to store blind. Please keep the **Write** token link somewhere safe, as you will need it for retrieving the data from your blind copy later on.

Then you create a **Blind** link and import this blind repository into the backup device.

### Retrieving Information from Blind Repositories

If you accidentally delete a _**repository**_ from your primary device, what you can do is go to **'Import _Repository_'**, copy and paste the **WRITE** link (which you kept somewhere safe!*) into the provided f
ield, and that's it. Once your primary device connects with your backup device, they will sync - i.e.: the primary _**repository**_ will automatically sync with your backup _**repository**_ and receive all the f
iles that _**repository**_ contains.

#### **Note:** 
If you add files to your primary _**repository**_, that addition will be propagated to your backup _**repository**_ too (if your backup device is connected/online. That means that your backup _**repository**_ will automatically receive all updates from your primary _**repository**_. However, if you delete any files in your primary _**repository**_, then that deletion will be propagated too, and you won't be able to retrieve those files. **Ouisync** is currently primarily a synchronization tool and not a secure backup tool. The selective syncing, and creating snapshots in time that will allow you to go back to the previous version of your _**repository**_ is planned for development in future **Ouisync** releases.

#### **Notice:** if you lose your **'Write'** link for the backup _**repository**_, you won't be able to retrieve data from that blind copy. 
{{% /markdown %}}
</details>
{{% /markdown %}}
</div>

<div class="faq-subsection">
{{% markdown %}}

## Sharing 

<details>
<summary>
<a name="sharing">
How can I share my repository with my peers (or my other devices)?
</a>
</summary>
{{% markdown %}}
You can do this by tapping the three vertical dots next to the repository name which will open the Settings screen for that repository, and then tapping the Share symbol: {{< figure src="/img/share.png" alt="Select to import a repository" >}}

{{< figure src="/img/repo_settings.png" alt="Repository settings menu" >}}
  
If the peer (or device) with whom you want to share a _**repository**_ is nearby, they can tap on **'Import repository'** on their device and then scan the QR code displayed on your screen:
{{< figure src="/img/qr_code.png" alt="Import a repository with a QR code" >}}

This action will import a copy of your _**repository**_ onto your peer's device, including all the files and folders within it. 

If your peer is not nearby, you can share your repositories by generating a link to send to your peer (or your other device): 
{{< figure src="/img/generate_link.png" alt="Generate a shortlink to share a repository" >}}

You can copy the link and paste it into an email or any messaging application, or you can tap the Share link button which will open one of the apps you can use to send it. Your peers will need to copy and paste that link into the field provided when they tap **'Import Repository'** on their device. 
{{< figure src="/img/token_import.png" alt="Import repository, then paste the link" >}}

**PS:** To paste a link to the input field, you tap and hold your finger on it, until a small **Paste** button appears to tap: {{< figure src="/img/paste_token.png" alt="Tap and hold to paste the link" >}}

{{% /markdown %}}
</details>

<details>
<summary>
How do I decide which permissions to select when sharing a repository?
</summary>
{{% markdown %}}
### **Write**
  
{{< figure src="/img/write_permission.png" alt="A repository with Write permissions" >}}

If you want your peers to be able to add files, delete them, rename or move them within the repository that you shared with them, then you need to share your repository with Write permission.

An example use case for this level of permissions: _sharing photos with friends and family, or working collaboratively on a project._ 

### **Read**

{{< figure src="/img/read_permission.png" alt="A repository with Read permissions" >}}

If you want your peers to only be able to read the _**repository**_ contents, then select **Read permissions**. This means they will be able to open the files and read them, but they won't be able to add new files to your shared _**repository**_, nor move or delete any files from it.

An example use case would be _when you want to share the information regarding an event or news items, or maybe regarding certain products, or perhaps you are a teacher sharing some content with your students, etc. In all these you want the recipients to be able to read the contents but not change them._ 

### **Blind**

{{< figure src="/img/blind_permission.png" alt="A repository with Blind permissions" >}}

This level of permissions can be useful when you want to securely store your _**repository**_ as a backup. This means that the person or device with whom you shared your repository as **'blind'** won't be able to open the files to read them, nor make any changes to them. This way you can store your data securely on a friend's computer, for example. 
{{% /markdown %}}
</details>

<details>
<summary>
Can my peers re-share my token links? 
</summary>
{{% markdown %}}
Yes. They can generate the token links with the same permissions they had in the original token link that they received from you, or lower. 

This means that if a person has received a token link to import a _**repository**_ with **Write** permissions they are able to generate the same kind of link to share the same _**repository**_ with other people, or they can also generate links for the same _**repository**_ but with lower permissions (**Read** or **Blind**). 

If they imported a **_repository_** with **Read** permissions only, then they can share it with others as **Read** or **Blind**. If they imported your _**repository**_ as **Blind**, they can only share it as **Blind**. 
{{% /markdown %}}
</details>

<details>
<summary>
What happens if me and my peers upload the same file into Ouisync?
</summary>
{{% markdown %}}
Ouisync is capable of handling two different scenarios.

#### Peers who are online at the same time

If you and one or more peers upload the same file (for example Billy.jpg) to the same Ouisync _**repository**_ that another peer has already uploaded, Ouisync will detect this situation and ask if you want to ke
ep both files or replace one of them:

{{< figure src="/img/concurrent_edit.png" alt="Synchronous edits file handling" >}}

If you decide to keep both of them, the new one will have (1) added to the name and you will see both files on your Ouisync screen. If you decide to replace the existing one, then the new ones will overwrite it
and the old one will no longer exist.

#### Peers who are offline at the time of uploading the files

If you and one or more peers upload the same file (for example Free_Test-Data_1MB.docx) when you are offline and therefore not able to sync files immediately, your files will sync when you are able to connect to
 your peers again.  In the event of two or more files bearing the same name, Ouisync will detect this situation and add a random string at the end of the name of each file to distinguish them.  You can then view
 them and decide which one to keep, whether to rename them, etc.

{{< figure src="/img/free_test_data.png" alt="Asynchronous sync file handling" >}}

{{% /markdown %}}
</details>
{{% /markdown %}}
</div>

<div class="faq-subsection">
{{% markdown %}}

## File Management

<details>
<summary>
What happens if I delete files in my repository?
</summary>
{{% markdown %}}
File deletion is propagated to all replicas in existence -which means the same file that you deleted will be automatically deleted in the _**repositories**_ of all the peers with whom you have shared it.

Equally, if your peers delete any files in any of the _**repositories**_ that they have imported from you, their file deletions will be propagated to your device too. It works both ways -i.e.: _**repositories**_ shared  with **Write** permissions will sync with each other, including file edits, additions or deletions.

{{% /markdown %}}
</details>
<details>
<summary>
What happens if I rename files in my repository?
</summary>
{{% markdown %}}
If you rename files in your _**repository**_, the new file name will be propagated to the _**repositories**_ of all the peers that you shared your _**repository**_ with.
{{% /markdown %}}
</details>

<details>
<summary>
Can I move my files from one repository to another?
</summary>
{{% markdown %}}
No. At the moment you can only move files from one folder to another within the same _**repository**_. Moving files from one repository to another is planned for future releases of **Ouisync**.
{{% /markdown %}}
</details>
{{% /markdown %}}
</div>

<div class="faq-subsection">
{{% markdown %}}

## Privacy and Security

<details>
<summary>
Are my files stored on a server? Why?
</summary>
{{% markdown %}}
Yes. They are stored fully encrypted in transport as well as at rest and are not readable by the server.

The purpose of the server storage is to facilitate file syncing when peers are not online at the same time. If you want to share a _**repository**_ with a peer who is not online at the moment, your _**repository**_ data will be stored encrypted on the server and when your peer comes online and connects either to the server (or to your device) the files from the stored _**repository**_ will sync with the files in your peer's _**repository**_.
{{% /markdown %}}
</details>

<details>
<summary>
How can I connect to the server?
</summary>
{{% markdown %}}
This happens automatically when you share a _**repository**_ with a peer - you don't need to perform any additional actions.
{{% /markdown %}}
</details>

<details>
<summary>
Where is this server and who runs it?
</summary>
{{% markdown %}}
The Ouisync servers are physically located in Canada and are managed by eQualitie.
{{% /markdown %}}
</details>

<details>
<summary>
What private data does Ouisync use/store?
</summary>
{{% markdown %}}
**Ouisync** uses the IP addresses of your devices to be able to connect you with your peers in the peer-to-peer network. We don't store those IP addresses anywhere on our systems. We don't keep any other user data. 
{{% /markdown %}}
</details>

<details>
<summary>
How can I lock my repositories when I'm not actively using them?
</summary>
{{% markdown %}}
To lock your _**repositories**_ when not actively working on them, tap on the **Lock** button: (insert screenshot).

To unlock them, tap on the repository name or on this button: (insert screenshot).

If your _**repository**_ is protected by password, enter the password when prompted. Otherwise, just tap on the **Unlock** button and continue to work on your repository.

{{% /markdown %}}
</details>
{{% /markdown %}}
</div>

<div class="faq-subsection">
{{% markdown %}}

# Other FAQs

<details>
<summary>
What are the advantages of using Ouisync over Dropbox, Google, or other similar solutions?
</summary>
{{% markdown %}}
  
### Free to use
To be able to share files using Dropbox, you need to create a Dropbox account. This requires your name, email, and credit card. It also requires payment. 

**Ouisync** is entirely free and open source software. To share files using **Ouisync**, you only need to install the app. That's it. No payment is required.

### Anonymity
**Ouisync** does not require the creation of user accounts. With **Ouisync**, it is simply a matter of installing the app and using it. All users are completely anonymous.

### **Ouisync** is a **P2P** solution
This means that using **Ouisync** successfully does not depend on any central server anywhere. **Ouisync** makes use of decentralized peer-to-peer networking, which makes it an effective file-sharing app even in situations where well-known file-sharing servers (such as **Dropbox** or **Google Drive**) are unavailable.

{{% /markdown %}}
</details>

<details>
<summary>
How can I sync files with my peers or with my other devices without internet?
</summary>
{{% markdown %}}
In situations with limited internet availability, you will need to make sure some means of connecting to other devices still exists. 

This could be a WiFi signal available to all devices that want to share **Ouisync** _**repositories**_, or it could be intranet, a local network or similar technologies. 

Currently _**repositories**_ cannot be shared via Bluetooth. This feature is planned for future releases.
{{% /markdown %}}
</details>
{{% /markdown %}}
{{% /markdown %}}
</div>
</div>
</div>