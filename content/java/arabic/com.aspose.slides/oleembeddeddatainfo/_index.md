---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides للغة Java مرجع API
description: يمثل معلومات البيانات المضمنة لكائن OLE.
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

يمثل معلومات البيانات المضمنة لكائن OLE.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | إنشاء معلومات بيانات مضمنة جديدة لكائن OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | إنشاء نسخة جديدة من معلومات البيانات المضمنة لكائن OLE. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | إرجاع بيانات الملف لكائن OLE مضمّن قراءة فقط byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | إرجاع امتداد الملف للكائن OLE المضمن الحالي قراءة فقط String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

إنشاء معلومات بيانات مضمنة جديدة لكائن OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

إنشاء نسخة جديدة من معلومات البيانات المضمنة لكائن OLE.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| embeddedFileData | byte[] | بيانات الملف لكائن OLE مضمّن byte[]. |
| embeddedFileExtension | java.lang.String | امتداد الملف للكائن OLE المضمن الحالي String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

إرجاع بيانات الملف لكائن OLE مضمّن قراءة فقط byte[].

**القيمة المرجعة:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

إرجاع امتداد الملف للكائن OLE المضمن الحالي قراءة فقط String.

**القيمة المرجعة:**
java.lang.String