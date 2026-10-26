---
title: CaptionsCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Representeert een collectie van de gesloten ondertitels.
type: docs
url: /nl/com.aspose.slides/captionscollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Representeert een collectie van de ondertitels.
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
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

Retourneert de ondertitels op de opgegeven index. Alleen-lezen [ICaptions](../../com.aspose.slides/icaptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

Voegt WebVTT-ondertitels toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | java.lang.String | Het label van de ondertitels. |
| filePath | java.lang.String | Het pad naar het WebVTT-bestand. |

**Retour:**
[ICaptions](../../com.aspose.slides/icaptions) - De toegevoegde [ICaptions](../../com.aspose.slides/icaptions) instantie.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Voegt WebVTT-ondertitels toe aan het einde van de collectie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | java.lang.String | Het label van de ondertitels. |
| stream | java.io.InputStream | De invoerstream die gegevens in WebVTT-indeling bevat. |

**Retour:**
[ICaptions](../../com.aspose.slides/icaptions) - De toegevoegde [ICaptions](../../com.aspose.slides/icaptions) instantie.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Verwijdert de opgegeven ondertitels uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | De te verwijderen ondertitels. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert de ondertitels op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index van de te verwijderen ondertitels. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle ondertitels uit de collectie.

### getCount() {#getCount--}
```
public final int getCount()
```

Retourneert het aantal elementen in de collectie. Alleen-lezen int .

**Retour:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Een  System.Collections.Generic.IEnumerator1  die kan worden gebruikt om door de collectie te itereren.