---
title: ExternalResourceResolver
second_title: Aspose.Slides for Java API Referansı
description: Html ve Svg belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geriçağrı sınıfı.
type: docs
url: /tr/com.aspose.slides/externalresourceresolver/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Html ve Svg belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geriçağrı sınıfı.

--------------------

Bu çözücü kullanıldığında, istemci tarafından sağlanan HTML veya SVG dosyası sunucu yazılımının yerel veya ağ dosyasına erişmesine yol açarak bir güvenlik açığı oluşturabilir. Dikkatli kullanın. ExternalResourceResolver'ı hiç belirtmemeniz (sadece gömülü nesneler okunur) veya belirtilen uri'nin geçerli olup olmadığını kontrol eden bir alt sınıf oluşturmanız önerilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Temel ve göreceli URI'lerden mutlak URI'yi çözer. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Bir URI'yi gerçek kaynağı içeren bir nesneyle eşleştirir. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Temel ve göreceli URI'lerden mutlak URI'yi çözer.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | java.lang.String | Bağlantı nesnelerinin temel URI'sı |
| relativeUri | java.lang.String | Bağlantılı nesneye göreceli URI. |

**Dönüş Değeri:**
java.lang.String - Mutlak URI veya göreceli URI çözülemezse null.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Bir URI'yi gerçek kaynağı içeren bir nesneyle eşleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | java.lang.String | Nesneye mutlak URI. |

**Dönüş Değeri:**
java.io.InputStream - Bir InputStream nesnesi veya kaynak akıtılamazsa null.