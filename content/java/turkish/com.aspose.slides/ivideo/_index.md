---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Bir sunuma yerleştirilmiş videoyu temsil eder.
type: docs
url: /tr/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Bir sunuma yerleştirilmiş videoyu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContentType()](#getContentType--) | Bir videonun MIME türünü döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmış. |
| [getBinaryData()](#getBinaryData--) | Ses verisinin bir kopyasını döndürür. |
| [getStream()](#getStream--) | Okuma için Stream akışını döndürür. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Bir videonun MIME türünü döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmış. Salt-okunur String.

**Döndürür:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Ses verisinin bir kopyasını döndürür. Büyük miktarda veri durumunda, videonun verisinin belleğe gereksiz yere yüklenmesini veya OutOfMemoryException oluşmasını önlemek için \#getStream.getStream yöntemini kullanmayı düşünün. Salt-okunur byte[].

**Döndürür:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Okuma için Stream akışını döndürür. 'using' kullanın veya kullandıktan sonra akışı kapatın.

**Döndürür:**
java.io.InputStream - Okuma için akış.