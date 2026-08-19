---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Callback-interface die wordt gebruikt om externe bronnen te resolven tijdens het importeren van Html- en Svg-documenten.
type: docs
url: /nl/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Callback-interface die wordt gebruikt om externe bronnen te resolven tijdens het importeren van Html, Svg-documenten.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Bepaalt de absolute URI op basis van de basis- en relatieve URI's. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Koppelt een URI aan een object dat de daadwerkelijke bron bevat. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Bepaalt de absolute URI op basis van de basis- en relatieve URI's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | java.lang.String | Basis-URI van koppelende objecten |
| relativeUri | java.lang.String | Relatieve URI naar het gekoppelde object. |

**Retourwaarde:**
java.lang.String - Absolute URI of null als de relatieve URI niet kan worden bepaald.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Koppelt een URI aan een object dat de daadwerkelijke bron bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI naar het object. |

**Retourwaarde:**
java.io.InputStream - Een InputStream-object of null als de bron niet kan worden gestreamd.