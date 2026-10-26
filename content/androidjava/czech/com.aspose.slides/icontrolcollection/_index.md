---
title: IControlCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Sbírka ovládacích prvků ActiveX.
type: docs
url: /cs/com.aspose.slides/icontrolcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Sbírka ovládacích prvků ActiveX.
## Metody

| Metoda | Popis |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Odstraňuje ovládací prvek ActiveX ze sbírky. |
| [removeAt(int index)](#removeAt-int-) | Odstraňuje ovládací prvek ActiveX uložený na určené pozici ze sbírky. |
| [clear()](#clear--) | Odstraňuje všechny ovládací prvky ze sbírky. |
| [get_Item(int index)](#get-Item-int-) | Vrací ovládací prvek na určené pozici. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Vytváří a přidává nový ovládací prvek do sbírky. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Odstraňuje ovládací prvek ActiveX ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Ovládací prvek k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraňuje ovládací prvek ActiveX uložený na určené pozici ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index ovládacího prvku, který má být odstraněn. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraňuje všechny ovládací prvky ze sbírky.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Vrací ovládací prvek na určené pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index ovládacího prvku. |

**Návratová hodnota:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Vytváří a přidává nový ovládací prvek do sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| controlType | int | Typ ovládacího prvku, který se má přidat. |
| x | float | Souřadnice X levé strany rámce tvaru. |
| y | float | Souřadnice Y horní strany rámce tvaru. |
| width | float | Šířka rámce tvaru. |
| height | float | Výška rámce tvaru. |

**Návratová hodnota:**
[IControl](../../com.aspose.slides/icontrol) - Vytvořený ovládací prvek [IControl](../../com.aspose.slides/icontrol).