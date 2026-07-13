---
title: ICellCollection
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje kolekcję komórek.
type: docs
url: /pl/com.aspose.slides/icellcollection/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Reprezentuje kolekcję komórek.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca komórkę według jej pozycji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Zwraca komórkę według jej pozycji. Tylko do odczytu [ICell](../../com.aspose.slides/icell).

--------------------

Jedno obiekty CellEx może być zwrócone dla kilku indeksów w przypadku, gdy komórka jest scalona.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ICell](../../com.aspose.slides/icell)