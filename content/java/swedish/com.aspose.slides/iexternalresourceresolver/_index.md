---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to resolve external resources during Html Svg documents import.
type: docs
url: /sv/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Callback-gränssnitt som används för att lösa upp externa resurser vid import av Html- och Svg-dokument.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


Löser den absoluta URI:n från bas- och relativ-URI:er.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | java.lang.String | Bas-URI för länkande objekt |
| relativeUri | java.lang.String | Relativ URI till det länkade objektet. |

**Returnerar:**
java.lang.String - Absolut URI eller null om den relativa URI:n inte kan lösas upp.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```


Mappar en URI till ett objekt som innehåller den faktiska resursen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolut URI till objektet. |

**Returnerar:**
java.io.InputStream - Ett InputStream-objekt eller null om resursen inte kan strömmas.