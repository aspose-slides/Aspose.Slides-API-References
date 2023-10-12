---
title: DigitalSignature
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/digitalsignature/
---

## DigitalSignature class

 Digital signature in signed file.
 
| Name | Description |
| --- | --- |
| DigitalSignature(byte[], String) | Creates a new DigitalSignature object with the specified certificate. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| certData | byte[] | a byte array containing the certificate |
| password | String | Password required to access certificate. |

### Result
DigitalSignature


---


| Name | Description |
| --- | --- |
| DigitalSignature(String, String) | Creates a new DigitalSignature object with the specified certificate file path and password. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | Path to the file with certificate. |
| password | String | Password required to access certificate. |

### Result
DigitalSignature


---


| Name | Description |
| --- | --- |
| getCertificate () | Certificate object that was used to sign the document. Read-only byte[]. |

### Result
byte


---


| Name | Description |
| --- | --- |
| getComments () | The purpose of signature. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getSignTime () | The time when the document was signed. Read-only java.util.Date. |

### Result
Date


---


| Name | Description |
| --- | --- |
| isValid () | If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| setComments (String) | The purpose of signature. Read/write String. |


---


