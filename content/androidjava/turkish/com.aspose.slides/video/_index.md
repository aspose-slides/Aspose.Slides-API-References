---
title: Video
second_title: Aspose.Slides Android için Java API Referansı
description: Sunuma gömülmüş bir resmi temsil eder.
type: docs
url: /tr/com.aspose.slides/video/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Sunum içinde yerleştirilmiş bir resmi temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getContentType()](#getContentType--) | Bir videonun MIME tipini döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmıştır. |
| [getBinaryData()](#getBinaryData--) | Bir sesin verisinin kopyasını döndürür. |
| [getStream()](#getStream--) | Okuma için Stream akışını döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Bir videonun MIME tipini döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmıştır. Yalnızca okuma String.

**Döndürür:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Bir sesin verisinin kopyasını döndürür. Büyük miktarda veri durumunda, videonun verisinin belleğe gereksiz yere yüklenmesini veya OutOfMemoryException oluşmasını önlemek için \#getStream.getStream yönteminin kullanılmasını düşünün. Yalnızca okuma byte[].

**Döndürür:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Stream akışını okuma için döndürür. Kullanımdan sonra 'using' kullanın veya akışı kapatın.

**Döndürür:**
java.io.InputStream - Okuma için Stream.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent\_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject