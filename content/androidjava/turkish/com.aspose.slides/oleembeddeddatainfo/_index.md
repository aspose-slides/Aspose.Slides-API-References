---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides for Android via Java API Referansı
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

OLE nesnesi için gömülü veri bilgisi temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | OLE nesnesi için yeni gömülü veri bilgisi oluşturur. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | OLE nesnesi için yeni bir gömülü veri bilgisi örneği oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Gömülü OLE nesnesinin dosya verisini döndürür. Yalnızca okuma byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Mevcut gömülü OLE nesnesinin dosya uzantısını döndürür. Yalnızca okuma String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


OLE nesnesi için yeni gömülü veri bilgisi oluşturur.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


OLE nesnesi için yeni bir gömülü veri bilgisi örneği oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| embeddedFileData | byte[] | Gömülü OLE nesnesinin dosya verisi byte[]. |
| embeddedFileExtension | java.lang.String | Mevcut gömülü OLE nesnesinin dosya uzantısı String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


Gömülü OLE nesnesinin dosya verisini döndürür. Yalnızca okuma byte[].

**Döndürür:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


Mevcut gömülü OLE nesnesinin dosya uzantısını döndürür. Yalnızca okuma String.

**Döndürür:**
java.lang.String