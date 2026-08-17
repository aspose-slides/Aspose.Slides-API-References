---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Referansı
description: Html ve Svg belgeleri içe aktarımı sırasında harici kaynakları çözmek için kullanılan geri arama arayüzü.
type: docs
url: /tr/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Html ve Svg belgeleri içe aktarımı sırasında harici kaynakları çözmek için kullanılan geri arama arayüzü.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Temel ve göreceli URI'lerden mutlak URI'yi çözer. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Bir URI'yi gerçek kaynağı içeren bir nesneye eşler. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


Temel ve göreceli URI'lerden mutlak URI'yi çözer.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | java.lang.String | Bağlantı nesnelerinin temel URI'si |
| relativeUri | java.lang.String | Bağlı nesneye göreceli URI. |

**Döndürür:**
java.lang.String - Mutlak URI veya göreceli URI çözülemezse null.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```


Bir URI'yi gerçek kaynağı içeren bir nesneye eşler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | java.lang.String | Nesnenin mutlak URI'si. |

**Döndürür:**
java.io.InputStream - Bir InputStream nesnesi veya kaynak akışa alınamıyorsa null.