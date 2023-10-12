---
title: PresentationInfo
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/presentationinfo/
---

## PresentationInfo class

 Information about presentation file
 
| [checkPassword] ([String]) | Checks whether a password is correct for a presentation protected with open password. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| password | [String] | The password to check. When the password is null or empty, this function returns false. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | if format is not supported to check passwords. |


---


| [checkWriteProtection] ([String]) | Checks whether a password to modify is correct for a write protected presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| password | [String] | The password to check. 1. You should check the ( #isWriteProtected) property before calling this function. 2. When password is null or empty, this function returns false. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | If a presentation is protected by a password to open or format does not support write protection |


---


| [getLoadFormat] () | Gets format of the binded presentation. Read-only LoadFormat. |

### Result
int


---


| [isEncrypted] () | Gets True if binded presentation is encrypted, otherwise False. Read-only boolean. |

### Result
boolean


---


| [isPasswordProtected] () | Gets a value that indicates whether a binded presentation is protected by a password to open. |

### Result
boolean


---


| [isWriteProtected] () | Gets a value that indicates whether a binded presentation is write protected. If the presentation is protected by a password to open, the property value equals NotDefined. |

### Result
byte


---


| [readDocumentProperties] () | Gets document properties of binded presentation. |

### Result
[DocumentProperties]


---


| [updateDocumentProperties] ([DocumentProperties]) | Updates properties of binded presentation. |


---


| [writeBindedPresentationToStream ] (PresentationInfo, [WriteStream]) | Writes binded presentation to stream. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentationinfo | PresentationInfo  | link to self |
| stream | [WriteStream] | The stream must be seekable and writable. |


---


| [writeBindedPresentation] ([String]) | Writes binded presentation to file. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | [String] | Presentation file. |


---


