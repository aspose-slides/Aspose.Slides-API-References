---
title: DrawingGuidesCollection
second_title: Aspose.Slides pro Java API Reference
description: Představuje kolekci upravitelných kreslicích vodítek.
type: docs
url: /cs/com.aspose.slides/drawingguidescollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Představuje kolekci upravitelných kreslicích vodítek.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrátí kreslicí vodítko podle indexu. |
| [add(byte orientation, float position)](#add-byte-float-) | Přidá kreslicí vodítko na konec kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní kreslicí vodítko na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [iterator()](#iterator--) | Vrátí enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou kolekci. |
| [getCount()](#getCount--) | Vrátí počet prvků v kolekci. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Vrátí kreslicí vodítko podle indexu. Pouze pro čtení [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

Přidá kreslicí vodítko na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| orientation | byte | Orientace kreslicího vodítka. |
| position | float | Pozice kreslicího vodítka v bodech. |

**Návratová hodnota:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní kreslicí vodítko na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index kreslicího vodítka, které má být smazáno. |

### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny prvky z kolekce.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Vrátí enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Vrátí java iterátor pro celou kolekci.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - java.util.Iterator pro celou kolekci.
### getCount() {#getCount--}
```
public final int getCount()
```

Vrátí počet prvků v kolekci. Pouze pro čtení int.

**Návratová hodnota:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

Zkopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |