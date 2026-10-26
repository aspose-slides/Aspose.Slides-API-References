---
title: ProtectionManager
second_title: 通过 Java API 的 Aspose.Slides for Android 参考
description: 演示文稿密码保护管理。
type: docs
url: /zh/com.aspose.slides/protectionmanager/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

演示文稿密码保护管理。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | 如果演示文稿受密码保护，则此属性有意义。 |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | 如果演示文稿受密码保护，则此属性有意义。 |
| [isEncrypted()](#isEncrypted--) | 获取一个指示此实例是否已加密的值。 |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | 如果演示文稿文件受密码保护且该文件的文档属性是公开的，则此属性有意义。 |
| [isWriteProtected()](#isWriteProtected--) | 获取指示此演示文稿是否受写保护的值。 |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 使用指定的密码加密演示文稿。 |
| [removeEncryption()](#removeEncryption--) | 移除加密。 |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 为此演示文稿设置指定密码的写保护。 |
| [removeWriteProtection()](#removeWriteProtection--) | 移除此演示文稿的写保护。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 判断演示文稿是否受密码保护以进行修改。 |
| [getEncryptionPassword()](#getEncryptionPassword--) | 获取用于演示文稿加密的密码。 |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 获取或设置只读建议。 |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 获取或设置只读建议。 |

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

如果演示文稿受密码保护，则此属性有意义。如果为 true，则文档属性在演示文稿文件中被加密。如果为 false，则文档属性是公开的，而演示文稿已加密。读/写布尔值。

**返回值：**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

如果演示文稿受密码保护，则此属性有意义。如果为 true，则文档属性在演示文稿文件中被加密。如果为 false，则文档属性是公开的，而演示文稿已加密。读/写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

获取一个指示此实例是否已加密的值。只读布尔值。

值：如果演示文稿是从加密文件加载的或调用了 \#encrypt(String).encrypt(String) 方法，则为 true；否则为 false。

**返回值：**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

如果演示文稿文件受密码保护且该文件的文档属性是公开的，则此属性有意义。true 表示仅从加密的演示文稿文件中加载文档属性而未使用密码。false 表示使用正确的密码加载整个加密的演示文稿，而不仅仅是文档属性。如果演示文稿未加密，则属性值始终为 false。如果加密文件的文档属性不是公开的，则属性值始终为 false。如果 Presentation.EncryptDocumentProperties 为 true，则 IsOnlyDocumentPropertiesLoaded 属性值始终为 false。只读布尔值。

**返回值：**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

获取一个指示此演示文稿是否受写保护的值。只读布尔值。

**返回值：**
boolean

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

使用指定的密码加密演示文稿。

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
获取或设置只读建议。读/写布尔值。

--------------------

Presentation pres = new Presentation();
 try {
     pres.getProtectionManager().setReadOnlyRecommended(true);
     pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
 } finally {
     if (pres != null) pres.dispose();
 }

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |