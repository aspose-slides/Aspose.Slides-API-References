---
title: PresentationInfo
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/presentationinfo/
---

## PresentationInfo class

 Information about presentation file
 

## Methods

| Name | Description |
| --- | --- |
| [checkPassword](checkpassword)(String) | Checks whether a password is correct for a presentation protected with open password. |
| [checkWriteProtection](checkwriteprotection)(String) | Checks whether a password to modify is correct for a write protected presentation. |
| [getLoadFormat](getloadformat)() | Gets format of the binded presentation. Read-only LoadFormat. |
| [isEncrypted](isencrypted)() | Gets True if binded presentation is encrypted, otherwise False. Read-only boolean. |
| [isPasswordProtected](ispasswordprotected)() | Gets a value that indicates whether a binded presentation is protected by a password to open. |
| [isWriteProtected](iswriteprotected)() | Gets a value that indicates whether a binded presentation is write protected. If the presentation is protected by a password to open, the property value equals NotDefined. |
| [readDocumentProperties](readdocumentproperties)() | Gets document properties of binded presentation. |
| [updateDocumentProperties](updatedocumentproperties)([DocumentProperties](../DocumentProperties)) | Updates properties of binded presentation. |
| [writeBindedPresentation](writebindedpresentation)(OutputStream) | Writes binded presentation to stream. |
| [writeBindedPresentation](writebindedpresentation)(String) | Writes binded presentation to file. |
