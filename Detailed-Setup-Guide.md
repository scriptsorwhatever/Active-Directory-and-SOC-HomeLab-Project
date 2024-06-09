
## Detailed Installation Guide

### Overview

This guide provides step-by-step instructions to set up a fully functional Active Directory environment integrated with Splunk and Kali Linux using VirtualBox. The project includes the installation and configuration of Windows Server, Ubuntu Server, Windows 10, and Kali Linux virtual machines, along with network setup and data forwarding to Splunk for monitoring and analysis.


![AD-Diagram](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/c6a76c1e-5c5c-4054-889e-31524b44c693)


## Windows 10 Target Machine Installation

![1](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/f1a7e99f-d186-4383-93fa-f0e923f99bcd)
![2](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/cb85f590-68aa-4d57-8e67-a3b087a04436)
![3](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/4822580b-befa-427b-bf23-15eeab79082d)
![4](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/7ead0a98-b5ec-47af-918b-65b0d44ec205)
![5](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/5ecd5b04-e2f8-41d8-830f-fb12764b742b)
![6](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/0af953cd-7064-4c32-9cd2-29947b4324cb)
![7](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/bb2e5d60-eabf-4b28-b50f-dd755dc7c0ce)
![8](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/94aee235-57fa-42b1-aa48-2c3fc515a6b1)
![9](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/6ae4e818-1aa8-4bd8-8d35-8ffd05e702b7)
![10](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/4cf4ac87-a7df-4682-83d1-33dac4725fd2)
![11](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/6da54107-f98a-46fa-bc24-9cc767e133ea)
![12](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/47a3a0f3-606a-4161-8221-01b296f5bef5)
![13](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/a5801b0c-34e1-46a8-8a80-5d4aafefc301)
![14](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/010d2d11-9d67-4467-9cc1-2bbbb22e7015)
![15](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/734638ef-412a-4a48-bdd7-8a8f63de35cf)
![16](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/969ba7f1-409b-4417-8fad-41cbee2270a3)
![17](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/1761b377-c235-43c2-af97-07523de724ca)
![18](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/d4c2f2af-7ef4-465d-ac28-349e581a5141)
![19](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/60f0e4ff-a55d-4aad-b558-db5735b4c3b7)
![20](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/b306b563-e7bb-44ab-8e8d-1fc14c4fb59e)


## Kali Machine Installation

![KALI-1 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/ec03a779-46d6-461e-a301-e0cc5c303098)
![KALI-2 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/4c661f4c-e996-42fe-83de-f1776fa9b01f)
![KALI-3 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/250c562a-b84e-4ead-aba5-9d1cd842860f)
![KALI-4 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/05bbd372-fb81-44af-8d84-00547144d576)
![KALI-5 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/c7946390-944a-4927-aa8a-e171451421b7)
![KALI-6 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/fa43a5db-ac00-452c-a4fe-389059807ca0)

### THE DEFAULT CREDENTIALS FOR THE KALI BOX ARE KALI:KALI

## Ubuntu Server Installation

![1 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/457be3d5-07c4-47a1-95fa-dcc76e15c484)
![2 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/4b87d6f2-f7fc-4937-b414-a9877d5ddf96)
![3 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/97964511-3731-49a9-af77-dd7b5a1f9ddc)
![4 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/c088142d-acf9-47d3-be0a-40bbd3fc4077)
![5 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/d9a97661-a569-4133-8c8c-39354aa7456d)
![6 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/c2893205-7053-4b62-afae-49ab1c11a805)
![7 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/4ca08e48-42e1-463e-88e1-4a4a53e1df0c)
![8 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/7dbdd256-819f-4c3c-a53f-62a55078e9fc)
![9 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/88b9c912-504e-4c87-a1f9-37ddf1d42fa5)
![10 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/e19aac57-c313-4d0c-b676-3e020e90084e)
![11 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/f86b1852-2fb0-43b3-b3aa-df6c10473905)
![12 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/11d913cb-ad25-4dac-8590-d1cb6b185a73)
![13 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/1f77982b-2003-4ab6-ad3a-3f1efb018777)
![14 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/ab63262b-5a82-4c15-899d-665acb289d49)
![15 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/d07cea64-1e15-44f8-8cfd-26c075fb74c4)
![16 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/c4a1cd8b-af44-4bb1-8a45-a1d5278ce16d)
![17 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/cea40179-37d1-4bdd-ab60-ee9a07de0c4a)
![18 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/98439aee-44e2-444a-a09a-06343e09f680)
![19 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/0d4c6978-9adf-4750-a06b-d962646277ce)
![20 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/9b145636-47b3-4b34-8991-1a866fee0805)
![21 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/7b88ecbd-944e-402c-9417-22bc1b8f0f5a)
![22 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/8141c584-855f-4f0b-a0c3-bddae994b2b2)
![23 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/5db9796c-e3a0-4744-8e7f-f2f1f91ad2ab)
![24 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/50e117cf-7994-4e5f-8c68-59f3c3ab4ce1)
![25 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/8c7ee286-7cc5-4153-8dfe-1c2f1c99e665)
![26 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/9a2b06d6-22b4-4115-bd1e-fe24e6aa6518)
![27 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/35e2f5d6-0db7-491d-a9d0-ce31223a237b)
![28 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/96241b6f-c330-406d-9cb8-a5eb0606fc19)

## Windows Server Installation

![1 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/e6a1f3a7-20f9-461a-ba14-c455b09fc253)
![2 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/4f44cf9c-2dde-462b-94f2-054b712f3ea0)
![3 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/378a8297-1dbc-4228-acfb-7a17fa22ceb4)
![4 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/e1f69336-08c7-4f20-a0f3-41e7bc2551b5)
![5 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/13c45c3d-c2bd-4319-962b-8188be076dc9)
![6 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/7f8cc2a3-13d7-4832-b922-2faac473260c)
![7 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/ad871d9e-bb1e-485d-9c66-69afa7cb20bc)
![8 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/356261a6-5dbc-477b-a11a-409132fff6c3)
![9 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/e97cfa01-cff8-45b4-8198-4d989875d23f)
![10 (2)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/3829c7a7-72b8-4a70-b92c-a01bbe6e85aa)
![11 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/37b16153-3254-448f-bca6-2603506c9dbe)
![12 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/66fdd5ac-c596-4787-b132-d2e09c747d1e)
![13 (1)](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/d84c8daf-7f50-42c9-8516-06171ae02d3e)

## Installing & configuring sysmon & Splunk

![1](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/ec3a2782-0c6e-4e7c-b904-e93f6ce5f39f)
![2](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/6c6a4917-d73b-41a2-a624-a1a4866913fa)
![3](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/1f029439-04a0-4cbc-99f0-0e21a3c97017)
![4](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/10954d23-839f-4fbb-b139-37ca5fe5aa8b)
![5](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/4a8dd7a0-5a5b-4306-a036-1ba4f3c3bd30)
![6](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/ca5543aa-e750-45cf-871c-cea94dab3e65)
![7](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/c0087c53-4f83-4b01-ad0e-e3db5a42b703)
![8](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/f765c93e-e2e0-4297-86e2-08dc790b221c)
![1](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/9936285e-a051-4e30-a495-5ab0d05933ce)
![2](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/22d88a38-b5af-4df5-bd4f-3071136a75c2)
![3](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/d1ba9b74-a0b5-4554-beaf-612c98f4f632)
![4](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/f0cf7ed8-a3f1-46dc-84ea-47b5c99caa04)
![5](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/a311556e-3dff-4eb0-8805-074a549a70e5)
![6](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/fbba2a54-a0ec-4a8b-a6c3-2e63cc716234)
![7](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/414dd019-b5bc-49d2-9a96-0fa096bae9a0)
![8](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/3c08630a-13d3-4ad3-989e-ad7e68fdbd4f)
![9](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/ec22c3bf-15a0-4e9a-9e32-bf73fcfa84ba)
![10](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/96c5993d-c8af-4130-a1d5-19c4a63981d9)
![11](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/4e68612c-a847-48c1-a927-4dd58397fc48)
![12](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/f88633f7-e238-4afa-b3ee-b947a1a29e39)
![13](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/defd2ce7-38a5-4628-b2f1-7a6c8f87817b)
![14](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/dd28308f-d0cb-4b59-a2c7-90f07412871c)
![15](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/c0ae1d0a-4f07-42e9-9e5f-976ad1345070)
![16](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/fa20c9e2-3691-48f8-afca-0e4d48a4afa4)
![17](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/c7b5cdb4-2e02-4a5a-be35-dbf301f19a8b)
![18](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/84739e21-2915-4fe0-8dc5-a39a93db8dc7)
![19](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/9d8c9057-2f96-4c1e-a93f-65d8269f13d9)
![20](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/316b8c62-92c6-4df8-bc53-0b6511da1c93)
![21](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/12f24f4e-5119-4957-af1b-3fc129b14f29)
![22](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/c38af263-ab53-43de-aa91-1127ef45b778)
![23](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/e816379a-f58d-4eea-bacb-935b0a77ddf5)
![24](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/fc94c9a1-9428-44c0-a33a-64f94e375aaf)
![25](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/469ad16a-354a-4c60-9a7f-9e6bef98efe0)
![26](https://github.com/scriptsorwhatever/Active-Directory-and-SOC-HomeLab-Project/assets/130718809/2168f08e-5702-4fe3-a04f-09aed205d8d2)

