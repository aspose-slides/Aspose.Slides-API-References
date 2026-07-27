---
title: AddClone()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma cópia de um slide especificado ao final da coleção.
type: docs
weight: 53
url: /pt/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) método


Adiciona uma cópia de um slide especificado ao final da coleção.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |

### Valor de Retorno

Novo slide.

## Observações



Ao clonar um slide entre diferentes apresentações, o mestre do slide também pode ser clonado. Um registro interno é usado para rastrear mestres clonados automaticamente e impedir a criação de múltiplos clones do mesmo slide mestre. A clonagem manual de slides mestres não será impedida nem registrada. Se precisar de mais controle sobre o processo de clonagem, use [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) ou [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) para clonar slides, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) ou [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) para clonar layouts e [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) para clonar mestres. 
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) método


Adiciona uma cópia de um slide especificado ao final da seção especificada.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) para um novo slide. |

### Valor de Retorno

Novo slide.

## Observações



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Agora a segunda seção contém uma cópia do primeiro slide.
```


## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) método


Adiciona uma cópia de um slide especificado ao final da coleção.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Slide de layout para um novo slide. |

### Valor de Retorno

Novo slide.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) método


Adiciona uma cópia de um slide de origem especificado ao final da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (o layout apropriado é o layout com o mesmo Tipo ou Nome do layout do slide de origem). Se não houver um layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide mestre para um novo slide. |
| allowCloneMissingLayout | **bool** | Se não houver um layout apropriado no mestre especificado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |

### Valor de Retorno

Novo slide.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [SlideCollection](../)
* Classe [ISection](../../isection/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)