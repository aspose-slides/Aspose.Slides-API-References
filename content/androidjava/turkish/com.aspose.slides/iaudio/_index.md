---
title: IAudio
second_title: Aspose.Slides for Android via Java API Referansı
description: Gömülü bir ses dosyasını temsil eder.
type: docs
url: /tr/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Gömülü bir ses dosyasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContentType()](#getContentType--) | Bir sesin MIME türünü döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmıştır. |
| [getBinaryData()](#getBinaryData--) | Bir sesin verilerinin kopyasını döndürür. |
| [getStream()](#getStream--) | Okuma için Stream akışını döndürür. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Bir sesin MIME türünü döndürür, (\#getBinaryData.getBinaryData) içinde kodlanmıştır. Salt okunur String.

**Döndürür:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Bir sesin verilerinin kopyasını döndürür. Büyük miktarda veri durumunda, ses verilerinin belleğe gereksiz yüklenmesini veya OutOfMemoryException oluşmasını önlemek için \#getStream.getStream yöntemini kullanmayı düşünün. Salt okunur byte[].

**Döndürür:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Okuma için Stream akışını döndürür. 'using' kullanın veya akışı kullandıktan sonra kapatın.

**Döndürür:**  
java.io.InputStream - Okuma için akış.