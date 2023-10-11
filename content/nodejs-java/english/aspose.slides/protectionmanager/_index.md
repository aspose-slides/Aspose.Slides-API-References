---
title: ProtectionManager
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/protectionmanager/
---

## ProtectionManager class

 Presentation password protection management.
 
| [checkWriteProtection] ([String]) Determines whether a presentation is a password protected to modify. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| password | [String] | The password for checking. 1. You should check the ( #isWriteProtected) property before calling this function. 2. When the password is null or empty, this function returns false. |

### Result
boolean


---


| [encrypt] ([String]) Encrypts Presentation with specified password. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| encryptionPassword | [String] | The password. |


---


| [getEncryptDocumentProperties] () This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean. |

### Result
boolean


---


| [getEncryptionPassword] () Gets the password which is used for presentation encryption. Read-only String. |

### Result
String


---


| [getReadOnlyRecommended] () Gets or sets read-only recommendation. Read/write boolean. |

### Result
boolean


---


| [isEncrypted] () Gets a value indicating whether this instance is encrypted. Read-only boolean. Value: true if presentation was loaded from encrypted file or #encrypt(String) function was called ; otherwise, false. |

### Result
boolean


---


| [isOnlyDocumentPropertiesLoaded] () This property makes sense, if presentation file is password protected and document properties of this file are public. Value of true means that only document properties are loaded from an encrypted presentation file without use of password. Value of false means that entire encrypted presentation is loaded with use of right password, not only document properties are loaded. If presentation isn't encrypted then property value is always false. If document properties of an encrypted file aren't public then property value is always false. If Presentation.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded property value is always false. Read-only boolean. |

### Result
boolean


---


| [isWriteProtected] () Gets a value indicating whether this presentation is write protected. Read-only boolean. |

### Result
boolean


---


| [removeEncryption] () Removes the encryption. |


---


| [removeWriteProtection] () Removes write protection for this presentation. |


---


| [setEncryptDocumentProperties] ([boolean]) This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean. |


---


| [setReadOnlyRecommended] ([boolean]) Gets or sets read-only recommendation. Read/write boolean. |


---


| [setWriteProtection] ([String]) Set write protection for this presentation with specified password. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| password | [String] | The password. |


---


