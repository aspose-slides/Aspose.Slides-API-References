---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides for Android via Java API 參考
description: 代表 OLE 物件的嵌入式資料資訊。
type: docs
url: /zh-hant/com.aspose.slides/oleembeddeddatainfo/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

代表 OLE 物件的嵌入式資料資訊。

## 建構子

| 建構函式 | 說明 |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | 建立新的 OLE 物件嵌入式資料資訊。 |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | 建立新的 OLE 物件嵌入式資料資訊。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 傳回嵌入式 OLE 物件的檔案資料，唯讀 byte[]。 |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 傳回目前嵌入式 OLE 物件的檔案副檔名，唯讀 String。 |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

建立新的 OLE 物件嵌入式資料資訊。

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

建立新的 OLE 物件嵌入式資料資訊。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| embeddedFileData | byte[] | 嵌入式 OLE 物件的檔案資料 byte[]。 |
| embeddedFileExtension | java.lang.String | 目前嵌入式 OLE 物件的檔案副檔名 String。 |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

傳回嵌入式 OLE 物件的檔案資料，唯讀 byte[]。

**傳回值:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

傳回目前嵌入式 OLE 物件的檔案副檔名，唯讀 String。

**傳回值:**
java.lang.String