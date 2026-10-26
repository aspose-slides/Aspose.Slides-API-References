---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java Reference API
description: Rozhraní zpětného volání používané k řešení externích zdrojů během importu dokumentů Html a Svg.
type: docs
url: /cs/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Rozhraní zpětného volání používané k řešení externích zdrojů během importu dokumentů Html, Svg.

## Metody

| Metoda | Popis |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Vyřeší absolutní URI ze základního a relativního URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapuje URI na objekt obsahující skutečný zdroj. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Vyřeší absolutní URI ze základního a relativního URI.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | java.lang.String | Základní URI propojujících objektů |
| relativeUri | java.lang.String | Relativní URI k propojenému objektu. |

**Vrací:**
java.lang.String - Absolutní URI nebo null, pokud nelze relativní URI vyřešit.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Mapuje URI na objekt obsahující skutečný zdroj.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolutní URI k objektu. |

**Vrací:**
java.io.InputStream - Objekt InputStream nebo null, pokud nelze zdroj streamovat.