---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides for Java API 參考文件
description: 代表 OLE 物件的嵌入資料資訊。
type: docs
url: /zh-hant/com.aspose.slides/oleembeddeddatainfo/
---
**繼承：**
java.lang.Object

**已實作的所有介面：**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

表示 OLE 物件的嵌入資料資訊。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | 建立 OLE 物件的新嵌入資料資訊。 |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | 建立 OLE 物件嵌入資料資訊的新實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 傳回嵌入 OLE 物件的檔案資料，只讀 byte[]。 |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 傳回目前嵌入 OLE 物件的檔案副檔名，只讀 String。 |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


建立 OLE 物件的新嵌入資料資訊。

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


建立 OLE 物件嵌入資料資訊的新實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| embeddedFileData | byte[] | 嵌入 OLE 物件的檔案資料 byte[]。 |
| embeddedFileExtension | java.lang.String | 目前嵌入 OLE 物件的檔案副檔名 String。 |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


傳回嵌入 OLE 物件的檔案資料，只讀 byte[]。

**傳回值：**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


傳回目前嵌入 OLE 物件的檔案副檔名，只讀 String。

**傳回值：**
java.lang.String