---
title: PresentationInfo
type: docs
weight: 0
url: /php-java/presentationinfo/
---

# PresentationInfo class

 Information about presentation file
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [checkPassword](/php-java/presentationinfo/checkpassword/)(String) | boolean | Checks whether a password is correct for a presentation protected with open password. |
| [checkWriteProtection](/php-java/presentationinfo/checkwriteprotection/)(String) | boolean | Checks whether a password to modify is correct for a write protected presentation. |
| [getLoadFormat](/php-java/presentationinfo/getloadformat/)() | int | Gets format of the binded presentation. Read-only LoadFormat. |
| [isEncrypted](/php-java/presentationinfo/isencrypted/)() | boolean | Gets True if binded presentation is encrypted, otherwise False. Read-only boolean. |
| [isPasswordProtected](/php-java/presentationinfo/ispasswordprotected/)() | boolean | Gets a value that indicates whether a binded presentation is protected by a password to open. |
| [isWriteProtected](/php-java/presentationinfo/iswriteprotected/)() | byte | Gets a value that indicates whether a binded presentation is write protected. If the presentation is protected by a password to open, the property value equals NotDefined. |
| [readDocumentProperties](/php-java/presentationinfo/readdocumentproperties/)() | IDocumentProperties | Gets document properties of binded presentation. |
| [updateDocumentProperties](/php-java/presentationinfo/updatedocumentproperties/)(IDocumentProperties) | void | Updates properties of binded presentation. |
| [writeBindedPresentation](/php-java/presentationinfo/writebindedpresentation/)(OutputStream) | void | Writes binded presentation to stream. |
| [writeBindedPresentation](/php-java/presentationinfo/writebindedpresentation/)(String) | void | Writes binded presentation to file. |
