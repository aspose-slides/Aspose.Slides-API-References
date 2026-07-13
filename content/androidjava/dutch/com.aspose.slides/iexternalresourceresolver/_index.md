---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: Callback-interface gebruikt om externe resources tijdens het importeren van Html- en Svg-documenten op te lossen.
type: docs
url: /nl/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Callback-interface gebruikt om externe resources tijdens het importeren van Html, Svg-documenten op te lossen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Lost de absolute URI op basis van de basis- en relatieve URI's. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Koppelt een URI aan een object dat de werkelijke resource bevat. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Lost de absolute URI op basis van de basis- en relatieve URI's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | java.lang.String | Basis-URI van koppelende objecten |
| relativeUri | java.lang.String | Relatieve URI naar het gekoppelde object. |

**Retour:**
java.lang.String - Absolute URI of null als de relatieve URI niet kan worden opgelost.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Koppelt een URI aan een object dat de werkelijke resource bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI naar het object. |

**Retour:**
java.io.InputStream - Een InputStream-object of null als de resource niet kan worden gestreamd.