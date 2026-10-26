---
title: ICaptionsCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van de ondertitels voor.
type: docs
url: /nl/com.aspose.slides/icaptionscollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Stelt een collectie van ondertitels voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de ondertitels op de opgegeven index. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Voegt WebVTT-ondertitels toe aan het einde van de collectie. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Voegt WebVTT-ondertitels toe aan het einde van de collectie vanuit een stream. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Verwijdert de opgegeven ondertitels uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de ondertitels op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle ondertitels uit de collectie. |
| [getCount()](#getCount--) | Retourneert het aantal elementen in de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


Retourneert de ondertitels op de opgegeven index. Alleen-lezen [ICaptions](../../com.aspose.slides/icaptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourwaarde:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


Voegt WebVTT-ondertitels toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | java.lang.String | Het label van de ondertitels. |
| filePath | java.lang.String | Het pad naar het WebVTT-bestand. |

**Retourwaarde:**
[ICaptions](../../com.aspose.slides/icaptions) - De toegevoegde [ICaptions](../../com.aspose.slides/icaptions) instantie.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


Voegt WebVTT-ondertitels toe aan het einde van de collectie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | java.lang.String | Het label van de ondertitels. |
| stream | java.io.InputStream | De invoer-stream met gegevens in WebVTT-formaat. |

**Retourwaarde:**
[ICaptions](../../com.aspose.slides/icaptions) - De toegevoegde [ICaptions](../../com.aspose.slides/icaptions) instantie.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


Verwijdert de opgegeven ondertitels uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | De ondertitels die verwijderd moeten worden. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert de ondertitels op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index van de ondertitels die verwijderd moeten worden. |

### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle ondertitels uit de collectie.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Retourneert het aantal elementen in de collectie. Alleen-lezen  int .

**Retourwaarde:**
int