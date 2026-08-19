---
title: CaptionsCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling van de gesloten ondertitels voor.
type: docs
url: /nl/com.aspose.slides/captionscollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Stelt een verzameling van de gesloten ondertitels voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de gesloten ondertitels op de opgegeven index. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Voegt WebVTT-gesloten ondertitels toe aan het einde van de verzameling. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Voegt WebVTT-gesloten ondertitels toe aan het einde van de verzameling vanuit een stream. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Verwijdert de opgegeven gesloten ondertitels uit de verzameling. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de gesloten ondertitels op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle gesloten ondertitels uit de verzameling. |
| [getCount()](#getCount--) | Retourneert het aantal elementen in de verzameling. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de verzameling iterereert. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Retourneert de gesloten ondertitels op de opgegeven index. Alleen-lezen [ICaptions](../../com.aspose.slides/icaptions).

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


Voegt WebVTT-gesloten ondertitels toe aan het einde van de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | java.lang.String | Het label van de gesloten ondertitels. |
| filePath | java.lang.String | Het pad naar het WebVTT-bestand. |

**Retour:**
[ICaptions](../../com.aspose.slides/icaptions) - De toegevoegde [ICaptions](../../com.aspose.slides/icaptions) instantie.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


Voegt WebVTT-gesloten ondertitels toe aan het einde van de verzameling vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | java.lang.String | Het label van de gesloten ondertitels. |
| stream | java.io.InputStream | De invoerstream die gegevens in WebVTT-indeling bevat. |

**Retour:**
[ICaptions](../../com.aspose.slides/icaptions) - De toegevoegde [ICaptions](../../com.aspose.slides/icaptions) instantie.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Verwijdert de opgegeven gesloten ondertitels uit de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | De te verwijderen gesloten ondertitels. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert de gesloten ondertitels op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index van de te verwijderen gesloten ondertitels. |

### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle gesloten ondertitels uit de verzameling.

### getCount() {#getCount--}
```
public final int getCount()
```


Retourneert het aantal elementen in de verzameling. Alleen-lezen int .

**Retour:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Retourneert een enumerator die door de verzameling iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Een  System.Collections.Generic.IEnumerator1  die kan worden gebruikt om door de verzameling te itereren.