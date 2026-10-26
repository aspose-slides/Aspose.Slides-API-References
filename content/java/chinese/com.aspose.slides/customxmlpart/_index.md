---
title: CustomXmlPart
second_title: Aspose.Slides for Java API 参考
description: 表示自定义 xml 部分。
type: docs
url: /zh/com.aspose.slides/customxmlpart/
---
**继承:**
java.lang.Object

**已实现的接口:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

表示自定义 xml 部分。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getXmlData()](#getXmlData--) | 返回或设置 xml 数据。 |
| [setXmlData(byte[] value)](#setXmlData-byte---) | 返回或设置 xml 数据。 |
| [getXmlAsString()](#getXmlAsString--) | 返回或设置 xml 数据为 UTF-8 字符串。 |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | 返回或设置 xml 数据为 UTF-8 字符串。 |
| [getItemId()](#getItemId--) | 指定全局唯一标识符 (GUID)，该标识符在 Office Open XML 文档中唯一标识单个自定义 XML 部分。 |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | 指定全局唯一标识符 (GUID)，该标识符在 Office Open XML 文档中唯一标识单个自定义 XML 部分。 |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | 返回与自定义 XML 部分关联的 XML 架构集合。 |
| [remove()](#remove--) | 从演示文稿中移除自定义 xml 部分。 |

### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

返回或设置 xml 数据。读/写 byte[]。

**返回:**
byte[]

### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

返回或设置 xml 数据。读/写 byte[]。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

返回或设置 xml 数据为 UTF-8 字符串。读/写 String。

**返回:**
java.lang.String

### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

返回或设置 xml 数据为 UTF-8 字符串。读/写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

指定全局唯一标识符 (GUID)，该标识符在 Office Open XML 文档中唯一标识单个自定义 XML 部分。只读 java.util.UUID。

**返回:**
java.util.UUID

### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

指定全局唯一标识符 (GUID)，该标识符在 Office Open XML 文档中唯一标识单个自定义 XML 部分。只读 java.util.UUID。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

返回与自定义 XML 部分关联的 XML 架构集合。只读 String[]。

**返回:**
java.lang.String[]

### remove() {#remove--}
```
public final void remove()
```

从演示文稿中移除自定义 xml 部分。