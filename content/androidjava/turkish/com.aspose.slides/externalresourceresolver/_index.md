---
title: ExternalResourceResolver
second_title: Android için Aspose.Slides, Java API Referansı üzerinden
description: Html ve Svg belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri çağırma sınıfı.
type: docs
url: /tr/com.aspose.slides/externalresourceresolver/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Html ve Svg belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri çağırma sınıfı.

--------------------

Bu çözücü kullanıldığında, istemci tarafından sağlanan HTML veya SVG dosyası sunucu yazılımının yerel veya ağ dosyasına erişmesine neden olabilecek bir güvenlik açığı ortaya çıkabilir. Dikkatli kullanın. ExternalResourceResolver'ı hiç belirtmemeniz (sadece gömülü nesneler okunur) veya belirtilen uri'nin geçerli olup olmadığını kontrol eden bir alt sınıf oluşturmanız önerilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Temel ve göreli URI'lerden mutlak URI'yi çözer. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Bir URI'yi gerçek kaynağı içeren bir nesneye eşler. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Temel ve göreli URI'lerden mutlak URI'yi çözer.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | java.lang.String | Bağlayan nesnelerin temel URI'si |
| relativeUri | java.lang.String | Bağlanan nesneye göreli URI. |

**Dönen Değer:**
java.lang.String - Mutlak URI veya göreli URI çözülemezse null.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Bir URI'yi gerçek kaynağı içeren bir nesneye eşler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | java.lang.String | Nesnenin mutlak URI'si. |

**Dönen Değer:**
java.io.InputStream - Bir InputStream nesnesi veya kaynak akıştırılamazsa null.