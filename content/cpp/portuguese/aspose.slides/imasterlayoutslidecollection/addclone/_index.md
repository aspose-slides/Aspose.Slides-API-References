---
title: AddClone()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma cópia de um slide de layout especificado ao final da coleção.
type: docs
weight: 1
url: /pt/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

Adiciona uma cópia de um slide de layout especificado ao final da coleção.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |

### Valor de Retorno

Slide adicionado.
## Observações



1) O novo layout será vinculado ao slide mestre pai desta coleção de slides de layout. Portanto, isso é análogo a copiar/colar com a opção \"Use Destination Theme\" no PowerPoint. 2) Análogo a este método é o método [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) acessado através da propriedade [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 
## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)