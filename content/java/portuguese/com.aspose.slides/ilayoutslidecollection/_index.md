---
title: ILayoutSlideCollection
second_title: Referência da API Aspose.Slides para Java
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
| [get_Item(int index)](#get-Item-int-) | Retorna o slide de layout por índice. |
| [getByType(byte type)](#getByType-byte-) | Retorna o primeiro slide de layout do tipo especificado. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Remove um layout da coleção. |
| [removeUnused()](#removeUnused--) | Remove slides de layout não utilizados (slides de layout cujo HasDependingSlides é false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Retorna o slide de layout por índice. Somente leitura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

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

1) Para evitar o lançamento do PptxEditException verifique a propriedade HasDependingSlides do layout antes. 2) Você também pode usar o método [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) para simplificar o código. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Remove slides de layout não utilizados (slides de layout cujo HasDependingSlides é false).