---
title: HtmlExternalResolver
second_title: Aspose.Slides voor Java API-referentie
description: Callback-object dat wordt gebruikt door de HTML-importroutine om verwezen objecten, zoals afbeeldingen, te verkrijgen.
type: docs
url: /nl/com.aspose.slides/htmlexternalresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Callback-object dat wordt gebruikt door de HTML-importroutine om verwezen objecten, zoals afbeeldingen, te verkrijgen.

--------------------

Het gebruik van deze resolver kan een kwetsbaarheid veroorzaken wanneer een door de client geleverd HTML-bestand de serversoftware ertoe brengt een lokaal of netwerkbestand te verkrijgen. Gebruik dit met voorzichtigheid. Het wordt aanbevolen om HtmlExternalResolver niet op te geven (alleen ingebedde objecten worden gelezen) of een subklasse te maken die controleert of de opgegeven URI geldig is.

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Lost de absolute URI op op basis van de basis- en relatieve URI’s. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Koppelt een URI aan een object dat de daadwerkelijke bron bevat. |

### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Lost de absolute URI op op basis van de basis- en relatieve URI’s.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI van de koppelende objecten |
| relativeUri | java.lang.String | Relatieve URI naar het gekoppelde object. |

**Returns:**
java.lang.String - Absolute URI of null als de relatieve URI niet kan worden opgezocht.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Koppelt een URI aan een object dat de daadwerkelijke bron bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI naar het object. |

**Returns:**
java.io.InputStream - Een InputStream-object of null als de bron niet kan worden gestreamd.