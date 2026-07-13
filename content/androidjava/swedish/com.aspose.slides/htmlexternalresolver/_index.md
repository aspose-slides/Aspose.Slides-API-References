---
title: HtmlExternalResolver
second_title: Aspose.Slides för Android via Java API-referens
description: Callback-objekt som används av HTML-importrutinen för att hämta refererade objekt såsom bilder.
type: docs
url: /sv/com.aspose.slides/htmlexternalresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Callback-objekt som används av HTML-importrutinen för att hämta refererade objekt såsom bilder.

--------------------

Att använda denna resolver kan skapa en sårbarhet när en klienttillhandahållen HTML-fil får serverprogramvaran att hämta lokala eller nätverksfiler. Använd med försiktighet. Det rekommenderas att inte ange HtmlExternalResolver alls (endast inbäddade objekt kommer att läsas) eller skapa en underklass som kontrollerar om den angivna URI:n är giltig.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Löser den absoluta URI:n från bas- och relativa URI:er.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | java.lang.String | Bas-URI för länkningsobjekt |
| relativeUri | java.lang.String | Relativ URI till det länkade objektet. |

**Returnerar:**
java.lang.String - Absolut URI eller null om den relativa URI:n inte kan lösas.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Mappar en URI till ett objekt som innehåller den faktiska resursen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolut URI till objektet. |

**Returnerar:**
java.io.InputStream - Ett InputStream-objekt eller null om resursen inte kan strömmas.