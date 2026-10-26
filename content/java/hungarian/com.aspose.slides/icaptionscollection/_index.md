---
title: ICaptionsCollection
second_title: Aspose.Slides Java API referenciája
description: A zárt feliratok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/icaptionscollection/
---
**Minden implementált interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

A zárt feliratok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű zárt feliratot. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | WebVTT zárt feliratokat ad a gyűjtemény végéhez. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | WebVTT zárt feliratokat ad a gyűjtemény végéhez egy adatfolyamról. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Eltávolítja a megadott zárt feliratot a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a zárt feliratot a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes zárt feliratot a gyűjteményből. |
| [getCount()](#getCount--) | Visszaadja a gyűjtemény elemeinek számát. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

Visszaadja a megadott indexű zárt feliratot. Csak olvasható [ICaptions](../../com.aspose.slides/icaptions).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```

WebVTT zárt feliratokat ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | java.lang.String | A zárt felirat címkéje. |
| filePath | java.lang.String | A WebVTT fájl elérési útja. |

**Visszatérési érték:**
[ICaptions](../../com.aspose.slides/icaptions) - A hozzáadott [ICaptions](../../com.aspose.slides/icaptions) példány.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

WebVTT zárt feliratokat ad a gyűjtemény végéhez egy adatfolyamról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | java.lang.String | A zárt felirat címkéje. |
| stream | java.io.InputStream | A bemeneti adatfolyam, amely WebVTT formátumú adatot tartalmaz. |

**Visszatérési érték:**
[ICaptions](../../com.aspose.slides/icaptions) - A hozzáadott [ICaptions](../../com.aspose.slides/icaptions) példány.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

Eltávolítja a megadott zárt feliratot a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Az eltávolítandó zárt felirat. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a zárt feliratot a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó zárt felirat indexe. |
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes zárt feliratot a gyűjteményből.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja a gyűjtemény elemeinek számát. Csak olvasható  int .

**Visszatérési érték:**
int