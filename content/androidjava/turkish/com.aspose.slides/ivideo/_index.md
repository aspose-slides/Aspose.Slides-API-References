---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Bir sunuya gömülü bir videoyu temsil eder.
type: docs
url: /tr/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Bir sunuya gömülü bir videoyu temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContentType()](#getContentType--) | Bir videonun MIME tipini, (\#getBinaryData.getBinaryData) içinde kodlanmış olarak döndürür. |
| [getBinaryData()](#getBinaryData--) | Bir sesin verisinin bir kopyasını döndürür. |
| [getStream()](#getStream--) | Okuma için bir Stream akışı döndürür. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Bir videonun MIME tipini, (\#getBinaryData.getBinaryData) içinde kodlanmış olarak döndürür. Salt-okunur String.

**Döndürür:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Bir sesin verisinin bir kopyasını döndürür. Büyük miktarda veri durumunda, videonun verisinin belleğe gereksiz yere yüklenmesini veya OutOfMemoryException oluşmasını önlemek için \#getStream.getStream yönteminin kullanılmasını düşünün. Salt-okunur byte[].

**Döndürür:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Okuma için bir Stream akışı döndürür. 'using' kullanın veya kullanımdan sonra akışı kapatın.

**Döndürür:**
java.io.InputStream - Okuma için akış.