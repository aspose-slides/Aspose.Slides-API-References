---
title: IExternalResourceResolver
second_title: Aspose.Slides för Android via Java API-referens
description: Callback-gränssnitt som används för att lösa externa resurser under import av Html- och Svg-dokument.
type: docs
url: /sv/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Callback-gränssnitt som används för att lösa externa resurser under import av Html- och Svg-dokument.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Löser den absoluta URI:n från bas- och relativa URI:er. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mappar en URI till ett objekt som innehåller den faktiska resursen. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
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
public abstract InputStream getEntity(String absoluteUri)
```


Mappar en URI till ett objekt som innehåller den faktiska resursen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolut URI till objektet. |

**Returnerar:**
java.io.InputStream - Ett InputStream-objekt eller null om resursen inte kan strömmas.