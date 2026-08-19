---
title: CaptionsCollection
second_title: Aspose.Slides pro Java – Referenční příručka API
description: Představuje kolekci uzavřených titulků.
type: docs
url: /cs/com.aspose.slides/captionscollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Představuje kolekci uzavřených titulků.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací uzavřené titulky na zadaném indexu. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Přidává WebVTT uzavřené titulky na konec kolekce. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Přidává WebVTT uzavřené titulky na konec kolekce ze streamu. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Odstraňuje specifikované uzavřené titulky z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraňuje uzavřené titulky na zadaném indexu. |
| [clear()](#clear--) | Odstraňuje všechny uzavřené titulky z kolekce. |
| [getCount()](#getCount--) | Vrací počet prvků v kolekci. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Vrací uzavřené titulky na zadaném indexu. Pouze pro čtení [ICaptions](../../com.aspose.slides/icaptions).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```


Přidává WebVTT uzavřené titulky na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| label | java.lang.String | Štítek uzavřených titulků. |
| filePath | java.lang.String | Cesta k souboru WebVTT. |

**Návratová hodnota:**
[ICaptions](../../com.aspose.slides/icaptions) - Přidaná instance [ICaptions](../../com.aspose.slides/icaptions).
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


Přidává WebVTT uzavřené titulky na konec kolekce ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| label | java.lang.String | Štítek uzavřených titulků. |
| stream | java.io.InputStream | Vstupní stream obsahující data ve formátu WebVTT. |

**Návratová hodnota:**
[ICaptions](../../com.aspose.slides/icaptions) - Přidaná instance [ICaptions](../../com.aspose.slides/icaptions).
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Odstraňuje specifikované uzavřené titulky z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Uzavřené titulky k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraňuje uzavřené titulky na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index uzavřených titulků k odstranění. |

### clear() {#clear--}
```
public final void clear()
```


Odstraňuje všechny uzavřené titulky z kolekce.

### getCount() {#getCount--}
```
public final int getCount()
```


Vrací počet prvků v kolekci. Pouze pro čtení int .

**Návratová hodnota:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - A System.Collections.Generic.IEnumerator1 který lze použít k iteraci přes kolekci.