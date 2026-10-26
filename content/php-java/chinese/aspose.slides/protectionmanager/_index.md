---
title: ProtectionManager
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/protectionmanager/
---
## ProtectionManager 类

演示文稿密码保护管理。

### checkWriteProtection {#checkWriteProtection}

| 名称 | 描述 |
| --- | --- |
| checkWriteProtection (String) | 确定演示文稿是否受密码保护以进行修改。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 用于检查的密码。1. 调用此方法前应检查 ( #isWriteProtected) 属性。2. 当密码为 null 或空时，此方法返回 false。 |

**返回值：**
boolean


---

### encrypt {#encrypt}

| 名称 | 描述 |
| --- | --- |
| encrypt (String) | 使用指定密码加密 Presentation。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| encryptionPassword | String | 密码。 |

**返回值：**
void


---

### getEncryptDocumentProperties {#getEncryptDocumentProperties}

| 名称 | 描述 |
| --- | --- |
| getEncryptDocumentProperties () | 如果演示文稿受密码保护，则此属性有意义。如果为 true，则文档属性在演示文稿文件中被加密。如果为 false，则文档属性在演示文稿加密时是公开的。可读/写 布尔值。 |

**返回值：**
boolean


---

### getEncryptionPassword {#getEncryptionPassword}

| 名称 | 描述 |
| --- | --- |
| getEncryptionPassword () | 获取用于演示文稿加密的密码。只读 String。 |

**返回值：**
String


---

### getReadOnlyRecommended {#getReadOnlyRecommended}

| 名称 | 描述 |
| --- | --- |
| getReadOnlyRecommended () | 获取或设置只读推荐。可读/写 布尔值。 |

**返回值：**
boolean


---

### isEncrypted {#isEncrypted}

| 名称 | 描述 |
| --- | --- |
| isEncrypted () | 获取指示此实例是否已加密的值。只读 布尔值。值：如果演示文稿是从加密文件加载的或调用了 #encrypt(String) 方法，则为 true；否则为 false。 |

**返回值：**
boolean


---

### isOnlyDocumentPropertiesLoaded {#isOnlyDocumentPropertiesLoaded}

| 名称 | 描述 |
| --- | --- |
| isOnlyDocumentPropertiesLoaded () | 如果演示文稿文件受密码保护且该文件的文档属性是公开的，则此属性有意义。true 表示仅从加密的演示文稿文件中加载文档属性，而不使用密码。false 表示使用正确的密码加载整个加密的演示文稿，而不仅仅加载文档属性。如果演示文稿未加密，则属性值始终为 false。如果加密文件的文档属性不是公开的，则属性值始终为 false。如果 Presentation.EncryptDocumentProperties 为 true，则 IsOnlyDocumentPropertiesLoaded 属性值始终为 false。只读 布尔值。 |

**返回值：**
boolean


---

### isWriteProtected {#isWriteProtected}

| 名称 | 描述 |
| --- | --- |
| isWriteProtected () | 获取指示此演示文稿是否受写保护的值。只读 布尔值。 |

**返回值：**
boolean


---

### removeEncryption {#removeEncryption}

| 名称 | 描述 |
| --- | --- |
| removeEncryption () | 移除加密。 |

**返回值：**
void


---

### removeWriteProtection {#removeWriteProtection}

| 名称 | 描述 |
| --- | --- |
| removeWriteProtection () | 移除此演示文稿的写保护。 |

**返回值：**
void


---

### setEncryptDocumentProperties {#setEncryptDocumentProperties}

| 名称 | 描述 |
| --- | --- |
| setEncryptDocumentProperties (boolean) | 如果演示文稿受密码保护，则此属性有意义。如果为 true，则文档属性在演示文稿文件中被加密。如果为 false，则文档属性在演示文稿加密时是公开的。可读/写 布尔值。 |

**返回值：**
void


---

### setReadOnlyRecommended {#setReadOnlyRecommended}

| 名称 | 描述 |
| --- | --- |
| setReadOnlyRecommended (boolean) | 获取或设置只读推荐。可读/写 布尔值。 |

**返回值：**
void


---

### setWriteProtection {#setWriteProtection}

| 名称 | 描述 |
| --- | --- |
| setWriteProtection (String) | 使用指定密码为此演示文稿设置写保护。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 密码。 |

**返回值：**
void


---