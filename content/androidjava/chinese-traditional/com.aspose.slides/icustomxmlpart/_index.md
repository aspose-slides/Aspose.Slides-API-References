---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Represents custom xml part.
type: docs
url: /zh-hant/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

表示自訂 XML 部分。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | 取得或設定 XML 資料為 UTF-8 字串。 |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | 取得或設定 XML 資料為 UTF-8 字串。 |
| [getXmlData()](#getXmlData--) | 取得或設定 XML 資料。 |
| [setXmlData(byte[] value)](#setXmlData-byte---) | 取得或設定 XML 資料。 |
| [getItemId()](#getItemId--) | 指定唯一全域識別碼 (GUID)，唯一定義 Office Open XML 文件中的單一自訂 XML 部分。 |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | 指定唯一全域識別碼 (GUID)，唯一定義 Office Open XML 文件中的單一自訂 XML 部分。 |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | 取得與自訂 XML 部分關聯的 XML 架構集合。 |
| [remove()](#remove--) | 從簡報中移除自訂 XML 部分。 |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

取得或設定 XML 資料為 UTF-8 字串。 讀寫 String。

**回傳值:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

取得或設定 XML 資料為 UTF-8 字串。 讀寫 String。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

取得或設定 XML 資料。 讀寫 byte[]。

**回傳值:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

取得或設定 XML 資料。 讀寫 byte[]。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

指定唯一全域識別碼 (GUID)，唯一定義 Office Open XML 文件中的單一自訂 XML 部分。 唯讀 java.util.UUID。

**回傳值:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

指定唯一全域識別碼 (GUID)，唯一定義 Office Open XML 文件中的單一自訂 XML 部分。 唯讀 java.util.UUID。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

取得與自訂 XML 部分關聯的 XML 架構集合。 唯讀 String[]。

**回傳值:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

從簡報中移除自訂 XML 部分。