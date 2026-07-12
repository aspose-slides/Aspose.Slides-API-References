---
title: HtmlExternalResolver
second_title: Aspose.Slides für Android über Java API Reference
description: Callback-Objekt, das von der HTML-Importroutine verwendet wird, um referenzierte Objekte wie Bilder zu erhalten.
type: docs
url: /de/com.aspose.slides/htmlexternalresolver/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Callback-Objekt, das von der HTML-Importroutine verwendet wird, um referenzierte Objekte wie Bilder zu erhalten.

--------------------

Die Verwendung dieses Resolvers kann eine Schwachstelle erzeugen, wenn eine vom Client bereitgestellte HTML-Datei die Serversoftware veranlasst, lokale oder Netzwerkdateien zu beziehen. Mit Vorsicht verwenden. Es wird empfohlen, HtmlExternalResolver nicht anzugeben (es werden nur eingebettete Objekte gelesen) oder eine Unterklasse zu erstellen, die prüft, ob die angegebene URI gültig ist.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Methoden

| Methode | Beschreibung |
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


Löst die absolute URI aus der Basis-URI und den relativen URIs.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | java.lang.String | Basis-URI der verlinkenden Objekte |
| relativeUri | java.lang.String | Relative URI zum verlinkten Objekt. |

**Rückgabewert:**
java.lang.String - Absolute URI oder null, wenn die relative URI nicht aufgelöst werden kann.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI zum Objekt. |

**Rückgabewert:**
java.io.InputStream - Ein InputStream-Objekt oder null, wenn die Ressource nicht gestreamt werden kann.