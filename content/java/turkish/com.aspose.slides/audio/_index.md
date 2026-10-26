---
title: Audio
second_title: Aspose.Slides for Java API Referansı
description: Gömülü bir ses dosyasını temsil eder.
type: docs
url: /tr/com.aspose.slides/audio/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Gömülü bir ses dosyasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContentType()](#getContentType--) | Sesin MIME tipini, (\#getBinaryData.getBinaryData) içinde kodlanmış olarak döndürür. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Sesin MIME tipini, (\#getBinaryData.getBinaryData) içinde kodlanmış olarak döndürür. |
| [getBinaryData()](#getBinaryData--) | Ses verisinin bir kopyasını döndürür. |
| [getStream()](#getStream--) | Okuma için Stream akışını döndürür. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Sesin MIME tipini, (\#getBinaryData.getBinaryData) içinde kodlanmış olarak döndürür. Salt okunur String.

**Döndürür:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Sesin MIME tipini, (\#getBinaryData.getBinaryData) içinde kodlanmış olarak döndürür. Salt okunur String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Ses verisinin bir kopyasını döndürür. Büyük miktarda veri durumunda, ses verisinin belleğe gereksiz yere yüklenmesini veya OutOfMemoryException oluşmasını önlemek için #getStream.getStream metodunu kullanmayı düşünün. Salt okunur byte[].

**Döndürür:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Okuma için Stream akışını döndürür. 'using' kullanın ya da kullanım sonrası akışı kapatın.

**Döndürür:**
java.io.InputStream - Okuma için akış.