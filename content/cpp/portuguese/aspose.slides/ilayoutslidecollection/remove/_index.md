---
title: Remove()
second_title: Referência da API Aspose.Slides para C++
description: Remove um layout da coleção.
type: docs
weight: 27
url: /pt/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) método

Remove um layout da coleção.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | O slide de layout a ser removido da coleção. |

## Observações

1) Para evitar a exceção PptxEditException, verifique a propriedade HasDependingSlides do layout antes. 2) Você também pode usar o método [ILayoutSlide::Remove](../../ilayoutslide/remove/) para simplificar o código.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [ILayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)