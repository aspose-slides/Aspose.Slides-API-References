---
title: ITabCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci tabulátorů.
type: docs
url: /cs/com.aspose.slides/itabcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Reprezentuje kolekci tabulátorů.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [add(double position, int align)](#add-double-int-) | Přidá Tab do kolekce. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Přidá Tab do kolekce. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [ITab](../../com.aspose.slides/itab).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Přidá Tab do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | double | Pozice Tab. |
| align | int | Zarovnání Tab. |

**Návratová hodnota:**
[ITab](../../com.aspose.slides/itab) - Přidán Tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Přidá Tab do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Objekt Tab, který bude přidán na konec kolekce. |

**Návratová hodnota:**
int - Index, na který byl Tab přidán.
### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny prvky z kolekce.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní prvek na zadaném indexu kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn. |