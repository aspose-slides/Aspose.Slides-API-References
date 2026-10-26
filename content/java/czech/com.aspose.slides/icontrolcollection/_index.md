---
title: IControlCollection
second_title: Aspose.Slides pro Java – reference API
description: Kolekce ActiveX ovládacích prvků.
type: docs
url: /cs/com.aspose.slides/icontrolcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Kolekce ActiveX ovládacích prvků.
## Metody

| Metoda | Popis |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Odstraní ActiveX kontrolu ze sbírky. |
| [removeAt(int index)](#removeAt-int-) | Odstraní ActiveX kontrolu uloženou na zadané pozici ze sbírky. |
| [clear()](#clear--) | Odstraní všechny ovládací prvky ze sbírky. |
| [get_Item(int index)](#get-Item-int-) | Vrací kontrolu na zadané pozici. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Vytvoří a přidá novou kontrolu do sbírky. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```


Odstraní ActiveX kontrolu ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Ovládací prvek k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní ActiveX kontrolu uloženou na zadané pozici ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index ovládacího prvku k odstranění. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny ovládací prvky ze sbírky.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```


Vrací kontrolu na zadané pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index ovládacího prvku. |

**Vrací:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```


Vytvoří a přidá novou kontrolu do sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| controlType | int | Typ ovládacího prvku, který se má přidat. |
| x | float | Souřadnice X pro levý okraj rámce tvaru. |
| y | float | Souřadnice Y pro horní okraj rámce tvaru. |
| width | float | Šířka rámce tvaru. |
| height | float | Výška rámce tvaru. |

**Vrací:**
[IControl](../../com.aspose.slides/icontrol) - Vytvořený ovládací prvek [IControl](../../com.aspose.slides/icontrol).