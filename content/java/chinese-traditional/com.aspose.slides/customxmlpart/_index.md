---
title: CustomXmlPart
second_title: Aspose.Slides for Java API 參考
description: 表示自訂 XML 部分。
type: docs
url: /zh-hant/com.aspose.slides/customxmlpart/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

表示 custom xml 部分。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getXmlData()](#getXmlData--) | 傳回或設定 xml 資料。 |
| [setXmlData(byte[] value)](#setXmlData-byte---) | 傳回或設定 xml 資料。 |
| [getXmlAsString()](#getXmlAsString--) | 傳回或設定 xml 資料為 UTF-8 字串。 |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | 傳回或設定 xml 資料為 UTF-8 字串。 |
| [getItemId()](#getItemId--) | 指定全域唯一識別碼 (GUID)，唯一識別 Office Open XML 文件中的單一 custom XML 部分。 |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | 指定全域唯一識別碼 (GUID)，唯一識別 Office Open XML 文件中的單一 custom XML 部分。 |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | 傳回與 custom XML 部分相關聯的 XML 架構集合。 |
| [remove()](#remove--) | 從簡報中移除 custom xml 部分。 |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

傳回或設定 xml 資料。讀寫 byte[]。

**傳回：**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

傳回或設定 xml 資料。讀寫 byte[]。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

傳回或設定 xml 資料為 UTF-8 字串。讀寫 String。

**傳回：**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

傳回或設定 xml 資料為 UTF-8 字串。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

指定全域唯一識別碼 (GUID)，唯一識別 Office Open XML 文件中的單一 custom XML 部分。唯讀 java.util.UUID。

**傳回：**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

指定全域唯一識別碼 (GUID)，唯一識別 Office Open XML 文件中的單一 custom XML 部分。唯讀 java.util.UUID。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

傳回與 custom XML 部分相關聯的 XML 架構集合。唯讀 String[]。

**傳回：**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

從簡報中移除 custom xml 部分。