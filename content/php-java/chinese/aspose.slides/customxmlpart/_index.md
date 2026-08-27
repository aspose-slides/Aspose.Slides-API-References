---
title: CustomXmlPart
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/customxmlpart/
---
## CustomXmlPart 类

表示自定义 XML 部分。

### getItemId {#getItemId}

| 名称 | 描述 |
| --- | --- |
| getItemId () | 指定全局唯一标识符 (GUID)，该标识符唯一标识 Office Open XML 文档中的单个自定义 XML 部分。只读 java.util.UUID。 |

**返回：**
UUID


---


### getNamespaceSchemas {#getNamespaceSchemas}

| 名称 | 描述 |
| --- | --- |
| getNamespaceSchemas () | 返回与自定义 XML 部分关联的 XML 架构集合。只读 String[]。 |

**返回：**
String


---


### getXmlAsString {#getXmlAsString}

| 名称 | 描述 |
| --- | --- |
| getXmlAsString () | 返回或设置 XML 数据为 UTF-8 字符串。读/写 String。 |

**返回：**
String

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | value is empty or xml-data is invalid. |


---


### getXmlData {#getXmlData}

| 名称 | 描述 |
| --- | --- |
| getXmlData () | 返回或设置 XML 数据。读/写 byte[]。 |

**返回：**
byte

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | value is empty or xml-data is invalid. |


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove () | 将自定义 XML 部分从演示文稿中移除。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | Thrown if xml part is already removed. |


---


### setItemId {#setItemId}

| 名称 | 描述 |
| --- | --- |
| setItemId (UUID) | 指定全局唯一标识符 (GUID)，该标识符唯一标识 Office Open XML 文档中的单个自定义 XML 部分。只读 java.util.UUID。 |

**返回：**
void


---


### setXmlAsString {#setXmlAsString}

| 名称 | 描述 |
| --- | --- |
| setXmlAsString (String) | 返回或设置 XML 数据为 UTF-8 字符串。读/写 String。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | value is empty or xml-data is invalid. |


---


### setXmlData {#setXmlData}

| 名称 | 描述 |
| --- | --- |
| setXmlData (byte[]) | 返回或设置 XML 数据。读/写 byte[]。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | value is empty or xml-data is invalid. |


---