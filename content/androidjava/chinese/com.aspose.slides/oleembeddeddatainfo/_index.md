---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 OLE 对象的嵌入数据信息。
type: docs
url: /zh/com.aspose.slides/oleembeddeddatainfo/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

表示 OLE 对象的嵌入数据信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | 创建新的 OLE 对象嵌入数据信息。 |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | 创建 OLE 对象嵌入数据信息的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 返回嵌入 OLE 对象的文件数据（只读 byte[]）。 |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 返回当前嵌入 OLE 对象的文件扩展名（只读 String）。 |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

创建新的 OLE 对象嵌入数据信息。

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

创建 OLE 对象嵌入数据信息的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| embeddedFileData | byte[] | 嵌入 OLE 对象的文件数据 byte[]。 |
| embeddedFileExtension | java.lang.String | 当前嵌入 OLE 对象的文件扩展名 String。 |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

返回嵌入 OLE 对象的文件数据（只读 byte[]）。

**返回值：**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

返回当前嵌入 OLE 对象的文件扩展名（只读 String）。

**返回值：**
java.lang.String