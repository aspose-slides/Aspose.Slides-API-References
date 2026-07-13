---
title: IControlCollection
second_title: Aspose.Slides dla Androida - odwołanie do API Java
description: Zbiór kontrolek ActiveX.
type: docs
url: /pl/com.aspose.slides/icontrolcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Zbiór kontrolek ActiveX.
## Metody

| Metoda | Opis |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Usuwa kontrolkę ActiveX z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa kontrolkę ActiveX przechowywaną na określonej pozycji z kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie kontrolki z kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca kontrolkę znajdującą się na określonej pozycji. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Tworzy i dodaje nową kontrolkę do kolekcji. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Usuwa kontrolkę ActiveX z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Kontrolka do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa kontrolkę ActiveX przechowywaną na określonej pozycji z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks kontrolki do usunięcia. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie kontrolki z kolekcji.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Zwraca kontrolkę znajdującą się na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks kontrolki. |

**Zwraca:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Tworzy i dodaje nową kontrolkę do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| controlType | int | Typ kontrolki do dodania. |
| x | float | Współrzędna X lewego boku ramki kształtu. |
| y | float | Współrzędna Y górnego boku ramki kształtu. |
| width | float | Szerokość ramki kształtu. |
| height | float | Wysokość ramki kształtu. |

**Zwraca:**
[IControl](../../com.aspose.slides/icontrol) - Utworzona kontrolka [IControl](../../com.aspose.slides/icontrol).