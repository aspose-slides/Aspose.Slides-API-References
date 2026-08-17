---
title: ProtectionManager
second_title: Aspose.Slides for Java API 参考
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

Presentation密码保护管理。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | 如果Presentation受密码保护，此属性才有意义。 |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | 如果Presentation受密码保护，此属性才有意义。 |
| [isEncrypted()](#isEncrypted--) | 获取一个值，指示此实例是否已加密。 |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | 如果Presentation文件受密码保护且该文件的文档属性是公开的，此属性才有意义。 |
| [isWriteProtected()](#isWriteProtected--) | 获取一个值，指示此Presentation是否受写保护。 |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 使用指定密码加密Presentation。 |
| [removeEncryption()](#removeEncryption--) | 移除加密。 |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 使用指定密码为此Presentation设置写保护。 |
| [removeWriteProtection()](#removeWriteProtection--) | 移除此Presentation的写保护。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 确定Presentation是否受密码保护以进行修改。 |
| [getEncryptionPassword()](#getEncryptionPassword--) | 获取用于Presentation加密的密码。 |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 获取或设置只读建议。 |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 获取或设置只读建议。 |

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

如果Presentation受密码保护，此属性才有意义。如果为true，则文档属性在Presentation文件中被加密。如果为false，则在Presentation被加密的同时文档属性是公开的。可读写布尔值。

**返回值：**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

如果Presentation受密码保护，此属性才有意义。如果为true，则文档属性在Presentation文件中被加密。如果为false，则在Presentation被加密的同时文档属性是公开的。可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

获取一个值，指示此实例是否已加密。只读布尔值。

值：true if presentation was loaded from encrypted file or \#encrypt(String).encrypt(String) method was called ; otherwise, false.

**返回值：**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

如果Presentation文件受密码保护且该文件的文档属性是公开的，此属性才有意义。值为true表示仅从加密的Presentation文件中加载文档属性而不使用密码。值为false表示使用正确的密码加载整个加密的Presentation，而不仅仅加载文档属性。如果Presentation未加密，则属性值始终为false。如果加密文件的文档属性不是公开的，则属性值始终为false。如果Presentation.EncryptDocumentProperties为true，则IsOnlyDocumentPropertiesLoaded属性值始终为false。只读布尔值。

**返回值：**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

获取一个值，指示此Presentation是否受写保护。只读布尔值。

**返回值：**
boolean

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

使用指定密码加密Presentation。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encryptionPassword | java.lang.String | 密码。 |

### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

移除加密。

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

使用指定密码为此Presentation设置写保护。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | java.lang.String | 密码。 |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

移除此Presentation的写保护。

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

确定Presentation是否受密码保护以进行修改。

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | java.lang.String | 检查用的密码。 |

1. 在调用此方法之前，您应检查 (\#isWriteProtected.isWriteProtected) 属性。 2. 当密码为null或为空时，此方法返回false。 |

**返回值：**
boolean - True if the password is valid; otherwise, false.

### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

获取用于Presentation加密的密码。只读String。

**返回值：**
java.lang.String

### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

获取或设置只读建议。可读写布尔值。

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

**返回值：**
boolean

### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

获取或设置只读建议。可读写布尔值。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |