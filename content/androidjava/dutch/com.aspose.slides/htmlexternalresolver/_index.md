---
title: HtmlExternalResolver
second_title: Aspose.Slides voor Android via Java API-referentie
description: Callback-object dat door de HTML-importroutine wordt gebruikt om verwijzende objecten, zoals afbeeldingen, te verkrijgen.
type: docs
url: /nl/com.aspose.slides/htmlexternalresolver/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Callback-object dat door de HTML-importroutine wordt gebruikt om verwezen objecten, zoals afbeeldingen, te verkrijgen.

--------------------

Het gebruik van deze resolver kan een kwetsbaarheid veroorzaken wanneer een door de client geleverd HTML-bestand de serversoftware laat lokale of netwerklocaties benaderen. Gebruik met voorzichtigheid. Het wordt aanbevolen om HtmlExternalResolver helemaal niet op te geven (alleen ingesloten objecten worden gelezen) of een subclass te maken die controleert of de opgegeven uri geldig is.

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Berekent de absolute URI op basis van de basis- en relatieve URI's. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Map een URI naar een object dat de feitelijke bron bevat. |

### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Berekent de absolute URI op basis van de basis- en relatieve URI's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI of linking objects |
| relativeUri | java.lang.String | Relative URI to the linked object. |

**Retourwaarde:**
java.lang.String - Absolute URI or null if the relative URI cannot be resolved.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Map een URI naar een object dat de feitelijke bron bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI to the object. |

**Retourwaarde:**
java.io.InputStream - A InputStream object or null if resource cannot be streamed.