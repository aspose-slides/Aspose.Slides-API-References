---
title: IOleEmbeddedDataInfo
second_title: Aspose.Slides 在 Android 上的 Java API 参考
description: 表示 OLE 对象的嵌入数据信息。
type: docs
url: /zh/com.aspose.slides/ioleembeddeddatainfo/
---```
public interface IOleEmbeddedDataInfo
```

表示 OLE 对象的嵌入数据信息。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 返回嵌入 OLE 对象的文件数据，只读 byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 返回当前嵌入 OLE 对象的文件扩展名，只读 String。 |
### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public abstract byte[] getEmbeddedFileData()
```

返回嵌入 OLE 对象的文件数据，只读 byte[]。

**返回:**  
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public abstract String getEmbeddedFileExtension()
```

返回当前嵌入 OLE 对象的文件扩展名，只读 String。

**返回:**  
java.lang.String