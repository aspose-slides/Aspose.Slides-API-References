---
title: IExternalResourceResolver
second_title: Aspose.Slides für Java API-Referenz
description: Callback-Schnittstelle, die zum Auflösen externer Ressourcen während des Imports von Html- und Svg-Dokumenten verwendet wird.
type: docs
url: /de/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Callback-Schnittstelle, die zum Auflösen externer Ressourcen während des Imports von Html- und Svg-Dokumenten verwendet wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Löst die absolute URI aus den Basis- und relativen URIs auf. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Löst die absolute URI aus den Basis- und relativen URIs auf.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | java.lang.String | Basis-URI der verknüpfenden Objekte |
| relativeUri | java.lang.String | Relative URI zum verknüpften Objekt. |

**Rückgabe:**
java.lang.String - Absolute URI oder null, wenn die relative URI nicht aufgelöst werden kann.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI zum Objekt. |

**Rückgabe:**
java.io.InputStream - Ein InputStream-Objekt oder null, wenn die Ressource nicht gestreamt werden kann.