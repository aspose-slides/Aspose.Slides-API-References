---
title: Audio
second_title: Aspose.Slides for Android için Java API Referansı
description: Gömülü bir ses dosyasını temsil eder.
type: docs
url: /tr/com.aspose.slides/audio/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Gömülü bir ses dosyasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContentType()](#getContentType--) | Bir sesin MIME tipini döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmıştır. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Bir sesin MIME tipini döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmıştır. |
| [getBinaryData()](#getBinaryData--) | Bir sesin verisinin kopyasını döndürür. |
| [getStream()](#getStream--) | Okuma için Stream akışını döndürür. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Bir sesin MIME tipini döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmıştır. Salt okunur String.

**Döndürür:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Bir sesin MIME tipini döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmıştır. Salt okunur String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Bir sesin verisinin kopyasını döndürür. Büyük miktarda veri durumunda, ses verisinin belleğe gereksiz yere yüklenmesini veya OutOfMemoryException oluşmasını önlemek için \#getStream.getStream metodunun kullanılmasını düşünün. Salt okunur byte[].

**Döndürür:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Okuma için Stream akışını döndürür. 'using' kullanın veya kullanım sonrası akışı kapatın.

**Döndürür:**
java.io.InputStream - Okuma için akış.