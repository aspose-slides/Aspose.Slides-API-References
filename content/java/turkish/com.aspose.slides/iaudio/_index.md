---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /tr/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Gömülü bir ses dosyasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContentType()](#getContentType--) | Bir sesin MIME türünü döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmış. |
| [getBinaryData()](#getBinaryData--) | Ses verisinin bir kopyasını döndürür. |
| [getStream()](#getStream--) | Okumak için Stream akışı döndürür. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Bir sesin MIME türünü döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmış. Yalnızca okunur String.

**Döndürür:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Ses verisinin bir kopyasını döndürür. Büyük miktarda veri durumunda, ses verisinin gereksiz yere belleğe yüklenmesini veya OutOfMemoryException oluşmasını önlemek için \#getStream.getStream metodunun kullanılmasını düşünün. Yalnızca okunur byte[].

**Döndürür:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Okumak için Stream akışı döndürür. 'using' kullanın veya kullandıktan sonra akışı kapatın.

**Döndürür:**  
java.io.InputStream - Okuma için akış.