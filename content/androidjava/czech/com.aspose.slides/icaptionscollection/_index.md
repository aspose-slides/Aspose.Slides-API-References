---
title: ICaptionsCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci uzavřených titulků.
type: docs
url: /cs/com.aspose.slides/icaptionscollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Reprezentuje kolekci uzavřených titulků.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací titulky na zadaném indexu. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Přidá WebVTT titulky na konec kolekce. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Přidá WebVTT titulky na konec kolekce ze streamu. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Odstraní určené titulky z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní titulky na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny titulky z kolekce. |
| [getCount()](#getCount--) | Vrací počet prvků v kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

Vrací titulky na zadaném indexu. Pouze pro čtení [ICaptions](../../com.aspose.slides/icaptions).

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

Přidá WebVTT titulky na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| label | java.lang.String | Štítek titulků. |
| filePath | java.lang.String | Cesta k souboru WebVTT. |

**Vrací:**
[ICaptions](../../com.aspose.slides/icaptions) - Instance přidaného [ICaptions](../../com.aspose.slides/icaptions).
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

Přidá WebVTT titulky na konec kolekce ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| label | java.lang.String | Štítek titulků. |
| stream | java.io.InputStream | Vstupní stream obsahující data ve formátu WebVTT. |

**Vrací:**
[ICaptions](../../com.aspose.slides/icaptions) - Instance přidaného [ICaptions](../../com.aspose.slides/icaptions).
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

Odstraní určené titulky z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Titulky k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní titulky na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index titulků k odstranění. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny titulky z kolekce.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Vrací počet prvků v kolekci. Pouze pro čtení  int .

**Vrací:**
int