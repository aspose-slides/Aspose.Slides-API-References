---
title: HtmlExternalResolver
second_title: Aspose.Slides für Java API-Referenz
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

Callback-Objekt, das von der HTML-Import-Routine verwendet wird, um referenzierte Objekte wie Bilder zu erhalten.

--------------------

Die Verwendung dieses Resolvers kann eine Sicherheitslücke erzeugen, wenn eine vom Client bereitgestellte HTML-Datei die Serversoftware dazu bringt, lokale oder Netzwerkdateien abzurufen. Mit Vorsicht verwenden. Es wird empfohlen, HtmlExternalResolver überhaupt nicht anzugeben (nur eingebettete Objekte werden gelesen) oder eine Unterklasse zu erstellen, die prüft, ob die angegebene URI gültig ist.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Löst die absolute URI aus der Basis- und relativen URI auf. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält. |

### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Löst die absolute URI aus der Basis- und relativen URI auf.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | java.lang.String | Basis-URI der verknüpfenden Objekte |
| relativeUri | java.lang.String | Relative URI zum verknüpften Objekt. |

**Rückgabe:**
java.lang.String - Absolute URI oder null, falls die relative URI nicht aufgelöst werden kann.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Ordnet eine URI einem Objekt zu, das die tatsächliche Ressource enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI zum Objekt. |

**Rückgabe:**
java.io.InputStream - Ein InputStream-Objekt oder null, falls die Ressource nicht gestreamt werden kann.