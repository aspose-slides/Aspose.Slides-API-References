---
title: ProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Presentation password protection management.
type: docs
weight: 459
url: /androidjava/com.aspose.slides/protectionmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Presentation password protection management.
## Methods

| Method | Description |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | This property makes sense, if presentation is password protected. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | This property makes sense, if presentation is password protected. |
| [isEncrypted()](#isEncrypted--) | Gets a value indicating whether this instance is encrypted. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | This property makes sense, if presentation file is password protected and document properties of this file are public. |
| [isWriteProtected()](#isWriteProtected--) | Gets a value indicating whether this presentation is write protected. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Encrypts Presentation with specified password. |
| [removeEncryption()](#removeEncryption--) | Removes the encryption. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Set write protection for this presentation with specified password. |
| [removeWriteProtection()](#removeWriteProtection--) | Removes write protection for this presentation. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Determines whether a presentation is a password protected to modify. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Gets the password which is used for presentation encryption. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Gets or sets read-only recommendation. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Gets or sets read-only recommendation. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```


This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean.

**Returns:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```


This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Gets a value indicating whether this instance is encrypted. Read-only boolean.

Value: true if presentation was loaded from encrypted file or \#encrypt(String).encrypt(String) method was called ; otherwise, false.

**Returns:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```


This property makes sense, if presentation file is password protected and document properties of this file are public. Value of true means that only document properties are loaded from an encrypted presentation file without use of password. Value of false means that entire encrypted presentation is loaded with use of right password, not only document properties are loaded. If presentation isn't encrypted then property value is always false. If document properties of an encrypted file aren't public then property value is always false. If Presentation.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded property value is always false. Read-only boolean.

**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```


Gets a value indicating whether this presentation is write protected. Read-only boolean.

**Returns:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```


Encrypts Presentation with specified password.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encryptionPassword | java.lang.String | The password. |

### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```


Removes the encryption.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


Set write protection for this presentation with specified password.

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password. |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```


Removes write protection for this presentation.

--------------------

> ```
> This sample code shows you how to remove the write protection from a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


Determines whether a presentation is a password protected to modify.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password for checking.

--------------------

1. You should check the (\#isWriteProtected.isWriteProtected) property before calling this method. 2. When the password is null or empty, this method returns false. |

**Returns:**
boolean - True if the password is valid; otherwise, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```


Gets the password which is used for presentation encryption. Read-only String.

**Returns:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```


Gets or sets read-only recommendation. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```


Gets or sets read-only recommendation. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

