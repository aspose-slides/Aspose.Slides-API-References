---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل معلومات البيانات المدمجة لكائن OLE.
type: docs
url: /ar/com.aspose.slides/oleembeddeddatainfo/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

يمثل معلومات البيانات المدمجة لكائن OLE.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | ينشئ معلومات بيانات مدمجة جديدة لكائن OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Creates a new instance of an embedded data info for OLE object. |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | يرجع بيانات الملف لكائن OLE مدمج قراءة فقط byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | يرجع امتداد الملف للكائن OLE المدمج الحالي قراءة فقط String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


ينشئ معلومات بيانات مدمجة جديدة لكائن OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


ينشئ نسخة جديدة من معلومات بيانات مدمجة لكائن OLE.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| embeddedFileData | byte[] | بيانات الملف لكائن OLE مدمج byte[]. |
| embeddedFileExtension | java.lang.String | امتداد الملف للكائن OLE المدمج الحالي String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


يرجع بيانات الملف لكائن OLE مدمج قراءة فقط byte[].

**الإرجاع:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


يرجع امتداد الملف للكائن OLE المدمج الحالي قراءة فقط String.

**الإرجاع:**
java.lang.String