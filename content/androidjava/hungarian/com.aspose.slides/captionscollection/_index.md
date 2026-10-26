---
title: CaptionsCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A zárt feliratok gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/captionscollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

A zárt feliratok gyűjteményét reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű zárt feliratokat. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | WebVTT zárt feliratokat ad a gyűjtemény végéhez. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | WebVTT zárt feliratokat ad a gyűjtemény végéhez egy adatfolyamból. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Eltávolítja a megadott zárt feliratokat a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű zárt feliratokat. |
| [clear()](#clear--) | Eltávolítja az összes zárt feliratot a gyűjteményből. |
| [getCount()](#getCount--) | Visszaadja a gyűjtemény elemeinek számát. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Visszaadja a megadott indexű zárt feliratokat. Csak olvasható [ICaptions](../../com.aspose.slides/icaptions).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
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
public final ICaptions add(String label, InputStream stream)
```


WebVTT zárt feliratokat ad a gyűjtemény végéhez egy adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | java.lang.String | A zárt felirat címkéje. |
| stream | java.io.InputStream | A WebVTT formátumú adatokat tartalmazó bemeneti adatfolyam. |

**Visszatérési érték:**
[ICaptions](../../com.aspose.slides/icaptions) - A hozzáadott [ICaptions](../../com.aspose.slides/icaptions) példány.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Eltávolítja a megadott zárt feliratokat a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | A eltávolítandó zárt feliratok. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolítja a megadott indexű zárt feliratokat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó zárt feliratok indexe. |

### clear() {#clear--}
```
public final void clear()
```


Eltávolítja az összes zárt feliratot a gyűjteményből.

### getCount() {#getCount--}
```
public final int getCount()
```


Visszaadja a gyűjtemény elemeinek számát. Csak olvasható  int .

**Visszatérési érték:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Egy  System.Collections.Generic.IEnumerator1  amely használható a gyűjtemény bejárására.