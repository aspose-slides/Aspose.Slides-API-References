---
title: ExternalResourceResolver
second_title: Aspose.Slides för Java API-referens
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

Att använda denna resolver kan skapa en sårbarhet när en klienttillhandahållen HTML- eller SVG-fil får serverprogramvaran att hämta en lokal eller nätverksfil. Använd med försiktighet. Det rekommenderas att inte ange ExternalResourceResolver alls (endast inbäddade objekt kommer att läsas) eller att skapa en underklass som kontrollerar om den angivna uri:n är giltig.
## Konstruktörer

| Constructor | Description |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Metoder

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Löser den absoluta URI:n från bas- och relativa URI:er. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mappar en URI till ett objekt som innehåller den faktiska resursen. |
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
| baseUri | java.lang.String | Bas-URI för länkande objekt |
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