---
title: ExternalResourceResolver
second_title: Aspose.Slides für Java API-Referenz
description: Callback-Klasse, die zum Auflösen externer Ressourcen beim Import von Html- und Svg-Dokumenten verwendet wird.
type: docs
url: /de/com.aspose.slides/externalresourceresolver/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Callback-Klasse, die zum Auflösen externer Ressourcen während des Imports von Html- und Svg-Dokumenten verwendet wird.

--------------------

Die Verwendung dieses Resolvers kann eine Schwachstelle erzeugen, wenn eine vom Client bereitgestellte HTML- oder SVG-Datei die Serversoftware dazu veranlasst, lokale oder Netzwerkdateien abzurufen. Mit Vorsicht verwenden. Es wird empfohlen, ExternalResourceResolver überhaupt nicht anzugeben (es werden nur eingebettete Objekte gelesen) oder eine Unterklasse zu erstellen, die prüft, ob die angegebene URI gültig ist.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Löst die absolute URI aus Basis- und relativen URIs auf. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Ordnet einer URI ein Objekt zu, das die eigentliche Ressource enthält. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Löst die absolute URI aus Basis- und relativen URIs auf.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | java.lang.String | Basis-URI der verlinkenden Objekte |
| relativeUri | java.lang.String | Relative URI zum verlinkten Objekt. |

**Rückgabe:**
java.lang.String - Absolute URI oder null, wenn die relative URI nicht aufgelöst werden kann.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Ordnet einer URI ein Objekt zu, das die eigentliche Ressource enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI zum Objekt. |

**Rückgabe:**
java.io.InputStream - Ein InputStream-Objekt oder null, wenn die Ressource nicht gestreamt werden kann.