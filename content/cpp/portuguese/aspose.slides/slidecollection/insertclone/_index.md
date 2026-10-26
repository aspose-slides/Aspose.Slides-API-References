---
title: InsertClone()
second_title: Aspose.Slides para Referência da API C++
description: Insere uma cópia de um slide especificado na posição especificada da coleção.
type: docs
weight: 66
url: /pt/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) método


Insere uma cópia de um slide especificado na posição especificada da coleção.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |

### Valor de Retorno

Slide inserido.

## Observações



Ao clonar um slide entre diferentes apresentações, o mestre do slide também pode ser clonado. Um registro interno é usado para rastrear mestres clonados automaticamente a fim de evitar a criação de múltiplos clones do mesmo slide mestre. A clonagem manual de slides mestres não será impedida nem registrada. Se precisar de mais controle sobre o processo de clonagem, use [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) ou [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) para clonar slides e [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) para clonar mestres. 


O exemplo a seguir mostra como clonar em outra posição dentro de [Presentation](../../presentation/). 
```cpp
// Instanciar a classe Presentation que representa um arquivo de apresentação
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Clonar o slide desejado para o final da coleção de slides na mesma apresentação
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Clonar o slide desejado para o índice especificado na mesma apresentação
slides->InsertClone(2, slides->idx_get(1));
// Gravar a apresentação modificada no disco
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como clonar em outra posição dentro de [Presentation](../../presentation/). 
```cpp
// Instanciar a classe Presentation para carregar o arquivo de apresentação fonte
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Instanciar a classe Presentation para o PPTX de destino (onde o slide será clonado)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Gravar a apresentação de destino no disco
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) método


Insere uma cópia de um slide especificado na posição especificada da coleção.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Slide de layout para um novo slide. |

### Valor de Retorno

Slide inserido.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) método


Insere uma cópia de um slide de origem especificado na posição especificada da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (o layout apropriado é o layout com o mesmo Tipo ou Nome do layout do slide de origem). Se não houver um layout apropriado, então o layout do slide de origem será clonado (se allowCloneMissingLayout for verdadeiro) ou será lançada uma PptxEditException (se allowCloneMissingLayout for falso).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide mestre para um novo slide. |
| allowCloneMissingLayout | **bool** | Se não houver um layout apropriado no mestre especificado, então o layout do slide de origem será clonado (se allowCloneMissingLayout for verdadeiro) ou será lançada uma PptxEditException (se allowCloneMissingLayout for falso). |

### Valor de Retorno

Slide inserido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [SlideCollection](../)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)