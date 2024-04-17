---
title: ProtectionManager
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/protectionmanager/
---

## ProtectionManager class

 Presentation password protection management.
 
### checkWriteProtection {#checkWriteProtection}

| Name | Description |
| --- | --- |
| checkWriteProtection(String) | Determines whether a presentation is a password protected to modify. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| password | String | The password for checking. 1. You should check the ( #isWriteProtected) property before calling this method. 2. When the password is null or empty, this method returns false. |

 **Returns:**
boolean


---


### encrypt {#encrypt}

| Name | Description |
| --- | --- |
| encrypt(String) | Encrypts Presentation with specified password. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| encryptionPassword | String | The password. |


---


### getEncryptDocumentProperties {#getEncryptDocumentProperties}

| Name | Description |
| --- | --- |
| getEncryptDocumentProperties() | This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean. |

 **Returns:**
boolean


---


### getEncryptionPassword {#getEncryptionPassword}

| Name | Description |
| --- | --- |
| getEncryptionPassword() | Gets the password which is used for presentation encryption. Read-only String. |

 **Returns:**
String


---


### getReadOnlyRecommended {#getReadOnlyRecommended}

| Name | Description |
| --- | --- |
| getReadOnlyRecommended() | Gets or sets read-only recommendation. Read/write boolean. |

 **Returns:**
boolean


---


### isEncrypted {#isEncrypted}

| Name | Description |
| --- | --- |
| isEncrypted() | Gets a value indicating whether this instance is encrypted. Read-only boolean. Value: true if presentation was loaded from encrypted file or #encrypt(String) method was called ; otherwise, false. |

 **Returns:**
boolean


---


### isOnlyDocumentPropertiesLoaded {#isOnlyDocumentPropertiesLoaded}

| Name | Description |
| --- | --- |
| isOnlyDocumentPropertiesLoaded() | This property makes sense, if presentation file is password protected and document properties of this file are public. Value of true means that only document properties are loaded from an encrypted presentation file without use of password. Value of false means that entire encrypted presentation is loaded with use of right password, not only document properties are loaded. If presentation isn't encrypted then property value is always false. If document properties of an encrypted file aren't public then property value is always false. If Presentation.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded property value is always false. Read-only boolean. |

 **Returns:**
boolean


---


### isWriteProtected {#isWriteProtected}

| Name | Description |
| --- | --- |
| isWriteProtected() | Gets a value indicating whether this presentation is write protected. Read-only boolean. |

 **Returns:**
boolean


---


### removeEncryption {#removeEncryption}

| Name | Description |
| --- | --- |
| removeEncryption() | Removes the encryption. |


---


### removeWriteProtection {#removeWriteProtection}

| Name | Description |
| --- | --- |
| removeWriteProtection() | Removes write protection for this presentation. |


---


### setEncryptDocumentProperties {#setEncryptDocumentProperties}

| Name | Description |
| --- | --- |
| setEncryptDocumentProperties(boolean) | This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean. |


---


### setReadOnlyRecommended {#setReadOnlyRecommended}

| Name | Description |
| --- | --- |
| setReadOnlyRecommended(boolean) | Gets or sets read-only recommendation. Read/write boolean. |


---


### setWriteProtection {#setWriteProtection}

| Name | Description |
| --- | --- |
| setWriteProtection(String) | Set write protection for this presentation with specified password. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| password | String | The password. |


---


