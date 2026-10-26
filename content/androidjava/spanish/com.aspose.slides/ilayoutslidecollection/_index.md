---
title: ILayoutSlideCollection
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una clase base para una colección de diapositivas de diseño.
type: docs
url: /es/com.aspose.slides/ilayoutslidecollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Representa una clase base para una colección de diapositivas de diseño.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la diapositiva de diseño por índice. |
| [getByType(byte type)](#getByType-byte-) | Devuelve la primera diapositiva de diseño del tipo especificado. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Elimina un diseño de la colección. |
| [removeUnused()](#removeUnused--) | Elimina las diapositivas de diseño no usadas (diapositivas de diseño cuya HasDependingSlides es false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Devuelve la diapositiva de diseño por índice. Solo lectura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Devuelve la primera diapositiva de diseño del tipo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | byte | Un tipo de diapositiva de diseño a buscar. |

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) con el tipo especificado o null si no se encuentran diseños.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Elimina un diseño de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | La diapositiva de diseño a eliminar de la colección.

--------------------

1) Para evitar lanzar la PptxEditException, verifique la propiedad HasDependingSlides del diseño antes. 2) También puede usar el método [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) para simplificar el código. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Elimina las diapositivas de diseño no usadas (diapositivas de diseño cuya HasDependingSlides es false).