---
title: DigitalSignature
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/digitalsignature/
---

## DigitalSignature class

 Digital signature in signed file.
 
### DigitalSignature {#DigitalSignature}

| Name | Description |
| --- | --- |
| DigitalSignature(byte[], String) | Creates a new DigitalSignature object with the specified certificate. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| certData | byte[] | a byte array containing the certificate |
| password | String | Password required to access certificate. |

 **Returns:**
DigitalSignature


---


### DigitalSignature {#DigitalSignature}

| Name | Description |
| --- | --- |
| DigitalSignature(String, String) | Creates a new DigitalSignature object with the specified certificate file path and password. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | Path to the file with certificate. |
| password | String | Password required to access certificate. |

 **Returns:**
DigitalSignature


---


### getCertificate {#getCertificate}

| Name | Description |
| --- | --- |
| getCertificate () | Certificate object that was used to sign the document. Read-only byte[]. |

 **Returns:**
byte


---


### getComments {#getComments}

| Name | Description |
| --- | --- |
| getComments () | The purpose of signature. Read/write String. |

 **Returns:**
String


---


### getSignTime {#getSignTime}

| Name | Description |
| --- | --- |
| getSignTime () | The time when the document was signed. Read-only java.util.Date. |

 **Returns:**
Date


---


### isValid {#isValid}

| Name | Description |
| --- | --- |
| isValid () | If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only boolean. |

 **Returns:**
boolean


---


### setComments {#setComments}

| Name | Description |
| --- | --- |
| setComments (String) | The purpose of signature. Read/write String. |

 **Returns:**
void


---


