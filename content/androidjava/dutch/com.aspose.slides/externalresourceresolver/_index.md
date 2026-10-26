---
title: ExternalResourceResolver
second_title: Aspose.Slides voor Android via Java API-referentie
description: Callback-klasse die wordt gebruikt om externe bronnen op te lossen tijdens het importeren van Html- en Svg-documenten.
type: docs
url: /nl/com.aspose.slides/externalresourceresolver/
---
**Erfenis:**
java.lang.Object

**Alle Geïmplementeerde Interfaces:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Callback-klasse die wordt gebruikt om externe bronnen op te lossen tijdens het importeren van Html- en Svg-documenten.

--------------------

Het gebruik van deze resolver kan een kwetsbaarheid veroorzaken wanneer een door de client geleverd HTML- of SVG-bestand de serversoftware lokale of netwerkmappen laat ophalen. Gebruik dit met voorzichtigheid. Het wordt aanbevolen om ExternalResourceResolver helemaal niet op te geven (alleen ingebedde objecten worden gelezen) of een subklasse te maken die controleert of de opgegeven uri geldig is.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Bepaalt de absolute URI op basis van de basis- en relatieve URI's. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Koppelt een URI aan een object dat de feitelijke bron bevat. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Bepaalt de absolute URI op basis van de basis- en relatieve URI's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | java.lang.String | Basis-URI van koppelende objecten |
| relativeUri | java.lang.String | Relatieve URI naar het gekoppelde object. |

**Retourwaarde:**
java.lang.String - Absolute URI of null als de relatieve URI niet kan worden opgelost.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Koppelt een URI aan een object dat de feitelijke bron bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI naar het object. |

**Retourwaarde:**
java.io.InputStream - Een InputStream-object of null als de bron niet kan worden gestreamd.