---
title: ILayoutSlideCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma classe base para a coleção de slides de layout.
type: docs
url: /pt/com.aspose.slides/ilayoutslidecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Representa uma classe base para a coleção de slides de layout.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the layout slide by index. |
| [getByType(byte type)](#getByType-byte-) | Returns the first layout slide of specified type. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Removes a layout from the collection. |
| [removeUnused()](#removeUnused--) | Removes unused layout slides (layout slides whose HasDependingSlides is false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Retorna o slide de layout pelo índice. Somente leitura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Retorna o primeiro slide de layout do tipo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | byte | Um tipo de slide de layout a ser encontrado. |

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) com o tipo especificado ou null se nenhum layout for encontrado.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Remove um layout da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | O slide de layout a ser removido da coleção.

--------------------
1) Para evitar o lançamento da PptxEditException, verifique a propriedade HasDependingSlides do layout antes. 2) Você também pode usar o método [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) para simplificar o código. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Remove slides de layout não utilizados (slides de layout cujo HasDependingSlides é false).