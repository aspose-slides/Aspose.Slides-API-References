---
title: IOleEmbeddedDataInfo
second_title: Aspose.Slides for Java API 參考文件
description: 表示 OLE 物件的嵌入資料資訊。
type: docs
url: /zh-hant/com.aspose.slides/ioleembeddeddatainfo/
---```
public interface IOleEmbeddedDataInfo
```

表示 OLE 物件的嵌入資料資訊。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 返回嵌入 OLE 物件的檔案資料，唯讀 byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 返回目前嵌入 OLE 物件的檔案副檔名，唯讀 String. |
### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public abstract byte[] getEmbeddedFileData()
```

返回嵌入 OLE 物件的檔案資料，唯讀 byte[]。

**返回：**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public abstract String getEmbeddedFileExtension()
```

返回目前嵌入 OLE 物件的檔案副檔名，唯讀 String。

**返回：**
java.lang.String