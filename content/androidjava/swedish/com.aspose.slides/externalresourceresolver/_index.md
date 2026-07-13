---
title: ExternalResourceResolver
second_title: Aspose.Slides för Android via Java API-referens
description: Callback-klass som används för att lösa externa resurser vid import av Html- och Svg-dokument.
type: docs
url: /sv/com.aspose.slides/externalresourceresolver/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Callback-klass som används för att lösa externa resurser vid import av Html- och Svg-dokument.

--------------------

Att använda denna resolver kan skapa en sårbarhet när en klient tillhandahåller en HTML- eller SVG-fil som får serverprogramvaran att hämta en lokal eller nätverksfil. Använd med försiktighet. Det rekommenderas att inte specificera ExternalResourceResolver alls (endast inbäddade objekt kommer att läsas) eller skapa en underklass som kontrollerar om den angivna URI:n är giltig.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Löser den absoluta URI:n från bas- och relativa URI:er.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI of linking objects |
| relativeUri | java.lang.String | Relative URI to the linked object. |

**Returnerar:**
java.lang.String - Absolut URI eller null om den relativa URI:n inte kan lösas.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Kopplar en URI till ett objekt som innehåller den faktiska resursen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolut URI till objektet. |

**Returnerar:**
java.io.InputStream - Ett InputStream-objekt eller null om resursen inte kan strömmas.