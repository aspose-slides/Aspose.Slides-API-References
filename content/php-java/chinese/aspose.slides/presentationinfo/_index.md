---
title: PresentationInfo
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/presentationinfo/
---
## PresentationInfo 类

有关演示文稿文件的信息

### checkPassword {#checkPassword}

| 名称 | 描述 |
| --- | --- |
| checkPassword (String) | 检查受打开密码保护的演示文稿，密码是否正确。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 要检查的密码。当密码为 null 或为空时，此方法返回 false。 |

**返回值:**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果不支持检查密码的格式。 |

---


### checkWriteProtection {#checkWriteProtection}

| 名称 | 描述 |
| --- | --- |
| checkWriteProtection (String) | 检查对写保护的演示文稿，修改密码是否正确。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 要检查的密码。1. 在调用此方法之前应检查 ( #isWriteProtected) 属性。2. 当密码为 null 或为空时，此方法返回 false。 |

**返回值:**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 如果演示文稿受打开密码保护或格式不支持写保护。 |

---


### getLoadFormat {#getLoadFormat}

| 名称 | 描述 |
| --- | --- |
| getLoadFormat () | 获取绑定演示文稿的格式。只读 LoadFormat。 |

**返回值:**
int

---


### isEncrypted {#isEncrypted}

| 名称 | 描述 |
| --- | --- |
| isEncrypted () | 如果绑定的演示文稿已加密则返回 True，否则返回 False。只读 boolean。 |

**返回值:**
boolean

---


### isPasswordProtected {#isPasswordProtected}

| 名称 | 描述 |
| --- | --- |
| isPasswordProtected () | 获取一个值，指示绑定的演示文稿是否受打开密码保护。 |

**返回值:**
boolean

---


### isWriteProtected {#isWriteProtected}

| 名称 | 描述 |
| --- | --- |
| isWriteProtected () | 获取一个值，指示绑定的演示文稿是否受写保护。如果演示文稿受打开密码保护，则属性值等于 NotDefined。 |

**返回值:**
byte

---


### readDocumentProperties {#readDocumentProperties}

| 名称 | 描述 |
| --- | --- |
| readDocumentProperties () | 获取绑定演示文稿的文档属性。 |

**返回值:**
[DocumentProperties](../documentproperties)

---


### updateDocumentProperties {#updateDocumentProperties}

| 名称 | 描述 |
| --- | --- |
| updateDocumentProperties ([DocumentProperties](../documentproperties)) | 更新绑定演示文稿的属性。 |

**返回值:**
void

---


### writeBindedPresentation {#writeBindedPresentation}

| 名称 | 描述 |
| --- | --- |
| writeBindedPresentation (OutputStream) | 将绑定的演示文稿写入流。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 该流必须可定位且可写。 |

**返回值:**
void

---


### writeBindedPresentation {#writeBindedPresentation}

| 名称 | 描述 |
| --- | --- |
| writeBindedPresentation (String) | 将绑定的演示文稿写入文件。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| file | String | 演示文稿文件。 |

**返回值:**
void

---