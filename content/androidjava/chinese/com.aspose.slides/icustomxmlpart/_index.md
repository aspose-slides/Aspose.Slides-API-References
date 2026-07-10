---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: 表示自定义 xml 部分。
type: docs
url: /zh/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

表示自定义 xml 部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | 返回或设置 xml 数据，使用 UTF-8 字符串。 |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | 返回或设置 xml 数据，使用 UTF-8 字符串。 |
| [getXmlData()](#getXmlData--) | 返回或设置 xml 数据。 |
| [setXmlData(byte[] value)](#setXmlData-byte---) | 返回或设置 xml 数据。 |
| [getItemId()](#getItemId--) | 指定全局唯一标识符 (GUID)，在 Office Open XML 文档中唯一标识单个自定义 XML 部分。 |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | 指定全局唯一标识符 (GUID)，在 Office Open XML 文档中唯一标识单个自定义 XML 部分。 |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | 返回与自定义 XML 部分关联的 XML 架构集合。 |
| [remove()](#remove--) | 从演示文稿中移除自定义 xml 部分。 |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

返回或设置 xml 数据，使用 UTF-8 字符串。读取/写入 String.

**返回:**  
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

返回或设置 xml 数据，使用 UTF-8 字符串。读取/写入 String.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

返回或设置 xml 数据。读取/写入 byte[].

**返回:**  
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

返回或设置 xml 数据。读取/写入 byte[].

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

指定全局唯一标识符 (GUID)，在 Office Open XML 文档中唯一标识单个自定义 XML 部分。只读 java.util.UUID.

**返回:**  
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

指定全局唯一标识符 (GUID)，在 Office Open XML 文档中唯一标识单个自定义 XML 部分。只读 java.util.UUID.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

返回与自定义 XML 部分关联的 XML 架构集合。只读 String[].

**返回:**  
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

从演示文稿中移除自定义 xml 部分。