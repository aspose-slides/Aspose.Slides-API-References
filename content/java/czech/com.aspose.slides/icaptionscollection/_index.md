---
title: ICaptionsCollection
second_title: Aspose.Slides pro Java – reference API
description: Representuje kolekci uzavřených titulků.
type: docs
url: /cs/com.aspose.slides/icaptionscollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Represents a collection of the closed captions.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací uzavřené titulky na zadaném indexu. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Přidá uzavřené titulky WebVTT na konec kolekce. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Přidá uzavřené titulky WebVTT na konec kolekce ze streamu. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Odstraní zadané uzavřené titulky z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní uzavřené titulky na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny uzavřené titulky z kolekce. |
| [getCount()](#getCount--) | Vrací počet prvků v kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


Vrací uzavřené titulky na zadaném indexu. Pouze pro čtení [ICaptions](../../com.aspose.slides/icaptions).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


Přidá uzavřené titulky WebVTT na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| label | java.lang.String | Štítek uzavřených titulků. |
| filePath | java.lang.String | Cesta k souboru WebVTT. |

**Vrací:**
[ICaptions](../../com.aspose.slides/icaptions) - Přidanou [ICaptions](../../com.aspose.slides/icaptions) instanci.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


Přidá uzavřené titulky WebVTT na konec kolekce ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| label | java.lang.String | Štítek uzavřených titulků. |
| stream | java.io.InputStream | Vstupní stream obsahující data ve formátu WebVTT. |

**Vrací:**
[ICaptions](../../com.aspose.slides/icaptions) - Přidanou [ICaptions](../../com.aspose.slides/icaptions) instanci.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


Odstraní zadané uzavřené titulky z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Uzavřené titulky k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní uzavřené titulky na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index uzavřených titulků k odstranění. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny uzavřené titulky z kolekce.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Vrací počet prvků v kolekci. Pouze pro čtení  int .

**Vrací:**
int