---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: 演示文稿密码保护管理。
type: docs
url: /zh/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

演示文稿密码保护管理。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | 如果演示文稿受密码保护，则此属性有意义。 |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | 如果演示文稿受密码保护，则此属性有意义。 |
| [isEncrypted()](#isEncrypted--) | 获取一个值，指示此实例是否已加密。 |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | 如果演示文稿文件受密码保护且该文件的文档属性是公开的，则此属性有意义。 |
| [isWriteProtected()](#isWriteProtected--) | 获取一个值，指示此演示文稿是否受写保护。 |
| [getEncryptionPassword()](#getEncryptionPassword--) | 返回加密密码。 |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 获取或设置只读建议。 |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 获取或设置只读建议。 |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 使用指定密码对演示文稿进行加密。 |
| [removeEncryption()](#removeEncryption--) | 移除加密。 |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 使用指定密码为此演示文稿设置写保护。 |
| [removeWriteProtection()](#removeWriteProtection--) | 移除此演示文稿的写保护。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 确定演示文稿是否受密码保护以进行修改。 |

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

如果演示文稿受密码保护，则此属性有意义。如果为 true，则文档属性在演示文稿文件中被加密。如果为 false，则文档属性是公开的，而演示文稿已加密。读/写 布尔值。

**返回：**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

如果演示文稿受密码保护，则此属性有意义。如果为 true，则文档属性在演示文稿文件中被加密。如果为 false，则文档属性是公开的，而演示文稿已加密。读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

获取一个值，指示此实例是否已加密。只读布尔值。

值：true 表示演示文稿是从加密文件加载的或调用了 \#encrypt(String).encrypt(String) 方法；否则为 false。

**返回：**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

如果演示文稿文件受密码保护且该文件的文档属性是公开的，则此属性有意义。true 表示仅从加密的演示文稿文件中加载文档属性，而不使用密码。false 表示使用正确的密码加载整个加密的演示文稿，而不仅仅加载文档属性。如果演示文稿未加密，则属性值始终为 false。如果加密文件的文档属性不是公开的，则属性值始终为 false。如果 PresentationEx.EncryptDocumentProperties 为 true，则 IsOnlyDocumentPropertiesLoaded 属性值始终为 false。只读布尔值。

**返回：**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

获取一个值，指示此演示文稿是否受写保护。只读布尔值。

**返回：**
boolean

### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

返回加密密码。只读字符串。

**返回：**
java.lang.String

### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

获取或设置只读建议。读/写 布尔值。

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Returns:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```


Gets or sets read-only recommendation. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

使用指定密码对演示文稿进行加密。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encryptionPassword | java.lang.String | 密码。 |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

移除加密。

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```
使用指定密码为此演示文稿设置写保护。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | java.lang.String | 密码。 |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Removes write protection for this presentation.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)

确定演示文稿是否受密码保护以进行修改。

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
| password | java.lang.String | 用于检查的密码。 |

1. 在调用此方法之前，您应检查 (\#isWriteProtected.isWriteProtected) 属性。2. 当密码为 null 或空字符串时，此方法返回 false。 |

**返回：**
boolean - 如果密码有效则返回 true；否则返回 false。