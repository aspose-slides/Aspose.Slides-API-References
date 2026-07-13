---
title: IDrawingGuidesCollection
second_title: Aspose.Slides pro Android přes referenci Java API
description: Představuje kolekci nastavitelných kreslicích vodítek.
type: docs
url: /cs/com.aspose.slides/idrawingguidescollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Představuje kolekci nastavitelných kreslicích vodítek.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací kreslicí vodítko podle indexu. |
| [add(byte orientation, float position)](#add-byte-float-) | Přidá kreslicí vodítko na konec kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní kreslicí vodítko na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [getCount()](#getCount--) | Získá počet všech prvků v kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Vrací kreslicí vodítko podle indexu. Pouze pro čtení [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
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
public abstract void removeAt(int index)
```

Odstraní kreslicí vodítko na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index kreslicího vodítka, které má být smazáno. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny prvky z kolekce.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Získá počet všech prvků v kolekci. Pouze pro čtení int.

**Návratová hodnota:**
int