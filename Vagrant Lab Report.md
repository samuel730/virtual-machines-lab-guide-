# Vagrant Lab Report

## Student: Samuel Adesanya  
## Project: Virtual Machine Setup with Vagrant

---

## 1. Project Overview
This lab demonstrates how to install, configure, and manage a virtual machine using Vagrant and VirtualBox. The Apache web server is provisioned automatically.

---

## 2. Steps Performed
1. I downloaded virtualbox and vagrant

<img width="1167" height="465" alt="Screenshot 2026-02-20 113717" src="https://github.com/user-attachments/assets/2d25e3c2-d6cb-4998-8563-d3b9d608c891" />
<img width="1710" height="468" alt="Screenshot 2026-02-20 114105" src="https://github.com/user-attachments/assets/179bb9f6-aba3-4f75-a9e1-03f3d01ac676" />
<img width="1710" height="468" alt="Screenshot 2026-02-20 114105" src="https://github.com/user-attachments/assets/efc4cf12-3bbb-420e-b865-0323943cc4d1" />
<img width="1710" height="468" alt="Screenshot 2026-02-20 114105" src="https://github.com/user-attachments/assets/ddd0fffd-aacd-4961-a3f7-068c24b1c850" />
<img width="1417" height="214" alt="Screenshot 2026-02-20 133633" src="https://github.com/user-attachments/assets/e16f1d99-54e7-4300-abd6-0f245055dd0e" />
<img width="977" height="779" alt="Screenshot 2026-02-20 123008" src="https://github.com/user-attachments/assets/85bfe32c-8f19-422a-b5c6-9404c39bc2cd" />


2. Opened PowerShell in the project folder:
   `C:\Users\Oluwatunmise\Documents\workshop\virtual machines`
<img width="1396" height="60" alt="Screenshot 2026-02-20 133313" src="https://github.com/user-attachments/assets/2e2a95d9-6fc5-4c3c-a41c-ae0e026d4303" />
<img width="1493" height="86" alt="Screenshot 2026-02-20 133335" src="https://github.com/user-attachments/assets/66fe33f7-1f10-4f9a-b0de-49f7a31ffa80" />
<img width="1416" height="228" alt="Screenshot 2026-02-20 133352" src="https://github.com/user-attachments/assets/51b50e27-3fde-42d1-b0af-60d8766f87d9" />

3. Ran `vagrant up` to download Ubuntu 18.04 and start VM.
<img width="2541" height="436" alt="Screenshot 2026-02-20 123449" src="https://github.com/user-attachments/assets/fd618023-fad4-4d24-b91c-a291583cefe0" />
<img width="2377" height="1217" alt="Screenshot 2026-02-20 130729" src="https://github.com/user-attachments/assets/b79b4c1e-2246-4151-be4f-068193e94df9" />

4. Accessed VM using `vagrant ssh`.
<img width="2501" height="1370" alt="Screenshot 2026-02-20 130823" src="https://github.com/user-attachments/assets/82e703a6-270a-48f1-9188-40bc2559b852" />
<img width="1368" height="1365" alt="Screenshot 2026-02-20 130844" src="https://github.com/user-attachments/assets/38ac88a0-6d6f-41f6-a72e-b0d2e16cd0a0" />
<img width="2134" height="1357" alt="Screenshot 2026-02-20 130919" src="https://github.com/user-attachments/assets/7d9c5e37-1f94-4278-9395-ebe02cd17dc5" />
<img width="2241" height="1376" alt="Screenshot 2026-02-20 130940" src="https://github.com/user-attachments/assets/002b0c89-bf58-417a-abde-11731e032426" />
<img width="1779" height="1365" alt="Screenshot 2026-02-20 131004" src="https://github.com/user-attachments/assets/073472f4-15c0-4e21-b233-72c010a89451" />
<img width="1779" height="1365" alt="Screenshot 2026-02-20 131004 - Copy" src="https://github.com/user-attachments/assets/2eeaba9f-8c30-4b3a-915c-a847d0b1a628" />
<img width="1779" height="1365" alt="Screenshot 2026-02-20 131004" src="https://github.com/user-attachments/assets/21268138-8aa2-4393-be4b-745b807ca4db" />
<img width="1718" height="1367" alt="Screenshot 2026-02-20 131022" src="https://github.com/user-attachments/assets/6fa61b14-b438-475a-97b2-3001d53d000c" />
<img width="2432" height="1378" alt="Screenshot 2026-02-20 131049" src="https://github.com/user-attachments/assets/4fb8bc92-4265-41a6-ba05-0d88d28008e4" />
<img width="2321" height="1365" alt="Screenshot 2026-02-20 131105" src="https://github.com/user-attachments/assets/8fbd206e-834a-437c-9ad7-bb97463234b3" />
<img width="2369" height="1369" alt="Screenshot 2026-02-20 131121" src="https://github.com/user-attachments/assets/e6cc0adc-648c-4d6a-9a2f-b938aed51b4a" />
<img width="2312" height="1358" alt="Screenshot 2026-02-20 131135" src="https://github.com/user-attachments/assets/eca058ae-04c2-436e-beee-fa3de8d3861c" />
<img width="1759" height="1114" alt="Screenshot 2026-02-20 131150" src="https://github.com/user-attachments/assets/bf4e9c93-2a94-4d3e-973d-e21408b5c92a" />


5. Verified Apache installation by opening `http://localhost:8080` in browser.
<img width="1938" height="1186" alt="Screenshot 2026-02-20 131227" src="https://github.com/user-attachments/assets/55113d39-6d80-4f9d-a716-34671b0723a1" />
<img width="2015" height="1190" alt="Screenshot 2026-02-20 131244" src="https://github.com/user-attachments/assets/a4a6b0d2-0593-4144-9a4c-029f8a70f3f2" />
<img width="1762" height="583" alt="Screenshot 2026-02-20 131257" src="https://github.com/user-attachments/assets/ab0595ce-d3ac-43b6-960f-95987106dc74" />


6. Stopped and destroyed VM using:
<img width="1560" height="561" alt="Screenshot 2026-02-20 131523" src="https://github.com/user-attachments/assets/dd688903-f584-4402-b368-663c3bcb8151" />
<img width="1656" height="346" alt="Screenshot 2026-02-20 131759" src="https://github.com/user-attachments/assets/769a4e00-5fae-4a7e-8517-538d7cf1f846" />






```powershell
vagrant halt
vagrant destroy
