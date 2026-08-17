---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides for Java API Referansı
description: OLE nesnesi için gömülü veri bilgisini temsil eder.
type: docs
url: /tr/com.aspose.slides/oleembeddeddatainfo/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

OLE nesnesi için gömülü veri bilgisini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | OLE nesnesi için yeni gömülü veri bilgisi oluşturur. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | OLE nesnesi için gömülü bir veri bilgisinin yeni bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Gömülü bir OLE nesnesinin dosya verilerini döndürür. Salt okunur byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Mevcut gömülü OLE nesnesi için dosya uzantısını döndürür. Salt okunur String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

OLE nesnesi için yeni gömülü veri bilgisi oluşturur.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

OLE nesnesi için gömülü bir veri bilgisinin yeni bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| embeddedFileData | byte[] | Gömülü bir OLE nesnesinin dosya verileri byte[]. |
| embeddedFileExtension | java.lang.String | Mevcut gömülü OLE nesnesi için dosya uzantısı String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Gömülü bir OLE nesnesinin dosya verilerini döndürür. Salt okunur byte[].

**Döndürür:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Mevcut gömülü OLE nesnesi için dosya uzantısını döndürür. Salt okunur String.

**Döndürür:**
java.lang.String