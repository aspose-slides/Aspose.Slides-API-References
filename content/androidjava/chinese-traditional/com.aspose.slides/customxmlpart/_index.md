---
title: CustomXmlPart
second_title: Aspose.Slides for Android 之 Java API 參考
description: 表示自訂 XML 部分。
type: docs
url: /zh-hant/com.aspose.slides/customxmlpart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

表示自訂 XML 部分。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getXmlData()](#getXmlData--) | 返回或設定 xml 資料。 |
| [setXmlData(byte[] value)](#setXmlData-byte---) | 返回或設定 xml 資料。 |
| [getXmlAsString()](#getXmlAsString--) | 返回或設定 xml 資料為 UTF-8 字串。 |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | 返回或設定 xml 資料為 UTF-8 字串。 |
| [getItemId()](#getItemId--) | 指定全域唯一識別碼 (GUID)，唯一辨識 Office Open XML 文件中的單一自訂 XML 部分。 |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | 指定全域唯一識別碼 (GUID)，唯一辨識 Office Open XML 文件中的單一自訂 XML 部分。 |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | 返回與自訂 XML 部分相關聯的 XML 架構集合。 |
| [remove()](#remove--) | 從簡報中移除自訂 XML 部分。 |

### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

返回或設定 xml 資料。讀/寫 byte[]。

**返回:**
byte[]

### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

返回或設定 xml 資料。讀/寫 byte[]。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

返回或設定 xml 資料為 UTF-8 字串。讀/寫 String。

**返回:**
java.lang.String

### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

返回或設定 xml 資料為 UTF-8 字串。讀/寫 String。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

指定全域唯一識別碼 (GUID)，唯一辨識 Office Open XML 文件中的單一自訂 XML 部分。唯讀 java.util.UUID。

**返回:**
java.util.UUID

### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

指定全域唯一識別碼 (GUID)，唯一辨識 Office Open XML 文件中的單一自訂 XML 部分。唯讀 java.util.UUID。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

返回與自訂 XML 部分相關聯的 XML 架構集合。唯讀 String[]。

**返回:**
java.lang.String[]

### remove() {#remove--}
```
public final void remove()
```

從簡報中移除自訂 XML 部分。