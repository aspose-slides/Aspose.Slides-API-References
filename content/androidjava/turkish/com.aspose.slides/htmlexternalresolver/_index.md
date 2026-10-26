---
title: HtmlExternalResolver
second_title: Aspose.Slides for Android için Java API Referansı
description: HTML içe aktarma rutininde görüntüler gibi referans alınan nesneleri elde etmek için kullanılan geri arama nesnesi.
type: docs
url: /tr/com.aspose.slides/htmlexternalresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

HTML içe aktarma rutininde görüntüler gibi referans alınan nesneleri elde etmek için kullanılan geri arama nesnesi.

--------------------

Bu çözücü kullanıldığında, istemci tarafından sağlanan HTML dosyası sunucu yazılımının yerel veya ağ dosyasına erişmesine yol açabilecek bir güvenlik açığı oluşturabilir. Dikkatli kullanın. HtmlExternalResolver'ı hiç belirtmemeniz (sadece gömülü nesneler okunur) veya belirtilen URI’nin geçerli olup olmadığını kontrol eden bir alt sınıf oluşturmanız önerilir.
## Constructors

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Methods

| Yöntem | Açıklama |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Taban ve göreli URI'lerden mutlak URI'yi çözer. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Bir URI'yi gerçek kaynağı içeren bir nesneyle eşleştirir. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Taban ve göreli URI'lerden mutlak URI'yi çözer.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | java.lang.String | Bağlantı nesnelerinin temel URI'si |
| relativeUri | java.lang.String | Bağlı nesneye göreli URI. |

**Dönüş Değeri:**
java.lang.String - Mutlak URI veya göreli URI çözülemezse null.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Bir URI'yi gerçek kaynağı içeren bir nesneyle eşleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | java.lang.String | Nesnenin mutlak URI'si. |

**Dönüş Değeri:**
java.io.InputStream - Bir InputStream nesnesi veya kaynak akışa alınamazsa null.