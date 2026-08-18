---
title: HtmlExternalResolver
second_title: Aspose.Slides for Java API Referansı
description: HTML içe aktarma rutininde görüntüler gibi başvurulan nesneleri elde etmek için kullanılan geri arama nesnesi.
type: docs
url: /tr/com.aspose.slides/htmlexternalresolver/
---
**Kalıtım:**  
java.lang.Object

**Uygulanan Tüm Arabirimler:**  
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)  
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

HTML içe aktarma rutininde görüntüler gibi başvurulan nesneleri elde etmek için kullanılan geri arama nesnesi.

--------------------

Bu çözücü kullanıldığında, istemci tarafından sağlanan HTML dosyasının sunucu yazılımının yerel veya ağ dosyasına erişmesine neden olarak bir güvenlik açığı oluşturabilir. Dikkatli kullanın. HtmlExternalResolver'ı hiç belirtmemeniz (sadece gömülü nesneler okunur) veya belirtilen URI'nın geçerli olup olmadığını kontrol eden bir alt sınıf oluşturmanız önerilir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Temel ve göreli URI'lerden mutlak URI'yi çözer. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Bir URI'yi gerçek kaynağı içeren bir nesneye eşler. |

### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Temel ve göreli URI'lerden mutlak URI'yi çözer.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | java.lang.String | Bağlantı nesnelerinin temel URI'si |
| relativeUri | java.lang.String | Bağlı nesneye göreli URI. |

**Dönüş:**
java.lang.String - Mutlak URI ya da göreli URI çözülemezse null.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Bir URI'yi gerçek kaynağı içeren bir nesneye eşler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | java.lang.String | Nesnenin mutlak URI'si. |

**Dönüş:**
java.io.InputStream - Bir InputStream nesnesi ya da kaynak akışa alınamıyorsa null.