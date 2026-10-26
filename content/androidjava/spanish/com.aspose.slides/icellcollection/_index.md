---
title: ICellCollection
second_title: Aspose.Slides para Android vía referencia de la API Java
description: Representa una colección de celdas.
type: docs
url: /es/com.aspose.slides/icellcollection/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Representa una colección de celdas.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve una celda por su posición. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Devuelve una celda por su posición. Sólo lectura [ICell](../../com.aspose.slides/icell).

--------------------

Un objeto CellEx puede devolverse para varios índices en caso de que la celda esté fusionada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ICell](../../com.aspose.slides/icell)