---
title: Remove()
second_title: Referência da API Aspose.Slides para C++
description: Remove um layout da coleção.
type: docs
weight: 66
url: /pt/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) método

Remove um layout da coleção.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | O slide de layout a ser removido da coleção. |

## Observações

1) Para evitar o lançamento da PptxEditException, verifique a propriedade HasDependingSlides do layout antes. 2) Você também pode usar o método [ILayoutSlide::Remove](../../ilayoutslide/remove/) para simplificar o código.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [LayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)