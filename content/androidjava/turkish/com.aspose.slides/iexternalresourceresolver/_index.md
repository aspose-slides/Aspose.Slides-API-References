---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: HTML ve SVG belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri bildirim arabirimi.
type: docs
url: /tr/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

HTML ve SVG belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri bildirim arabirimi.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Temel ve göreli URI'lerden mutlak URI'yi çözer.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | java.lang.String | Bağlantı nesnelerinin temel URI'si |
| relativeUri | java.lang.String | Bağlı nesneye göreli URI. |

**Dönüş Değeri:**
java.lang.String - Mutlak URI veya göreli URI çözülemezse null.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Bir URI'yi gerçek kaynağı içeren bir nesneyle eşleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | java.lang.String | Nesneye mutlak URI. |

**Dönüş Değeri:**
java.io.InputStream - Bir InputStream nesnesi veya kaynak akılamazsa null.