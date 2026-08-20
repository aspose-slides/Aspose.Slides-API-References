---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Represents custom xml part.
type: docs
url: /zh-hant/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

表示自訂 xml 部分。
## 方法

| Method | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | 返回或設定 xml 資料為 UTF-8 字串。 |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | 返回或設定 xml 資料為 UTF-8 字串。 |
| [getXmlData()](#getXmlData--) | 返回或設定 xml 資料。 |
| [setXmlData(byte[] value)](#setXmlData-byte---) | 返回或設定 xml 資料。 |
| [getItemId()](#getItemId--) | 指定全域唯一識別碼 (GUID)，該識別碼唯一識別 Office Open XML 文件中的單一自訂 xml 部分。 |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | 指定全域唯一識別碼 (GUID)，該識別碼唯一識別 Office Open XML 文件中的單一自訂 xml 部分。 |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | 返回與自訂 xml 部分相關聯的 xml 架構集合。 |
| [remove()](#remove--) | 從簡報中移除自訂 xml 部分。 |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

返回或設定 xml 資料為 UTF-8 字串。 讀寫 String.

**傳回:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

返回或設定 xml 資料為 UTF-8 字串。 讀寫 String.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

返回或設定 xml 資料。 讀寫 byte[].

**傳回:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

返回或設定 xml 資料。 讀寫 byte[].

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

指定全域唯一識別碼 (GUID)，該識別碼唯一識別 Office Open XML 文件中的單一自訂 xml 部分。 唯讀 java.util.UUID.

**傳回:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

指定全域唯一識別碼 (GUID)，該識別碼唯一識別 Office Open XML 文件中的單一自訂 xml 部分。 唯讀 java.util.UUID.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

返回與自訂 xml 部分相關聯的 xml 架構集合。 唯讀 String[].

**傳回:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

從簡報中移除自訂 xml 部分。