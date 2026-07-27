---
title: InsertClone()
second_title: Referência da API Aspose.Slides para C++
description: Insere uma cópia de um slide mestre especificado na posição especificada da coleção. Slides de layout vinculados também serão copiados.
type: docs
weight: 105
url: /pt/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) método


Insere uma cópia de um slide mestre especificado na posição especificada da coleção. Slides de layout vinculados também serão copiados.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) para clonar. |

### Valor de Retorno

Slide mestre inserido.

## Observações



O exemplo a seguir mostra como clonar um slide mestre em outro PowerPoint [Presentation](../../presentation/). 
```cpp
// Instanciar a classe Presentation para carregar o arquivo de apresentação de origem
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Instanciar a classe Presentation para a apresentação de destino (onde o slide será clonado)
auto destPres = System::MakeObject<Presentation>();

// Instanciar ISlide a partir da coleção de slides na apresentação de origem junto com
// Slide mestre
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Obter Slides Mestres da apresentação de destino
auto masters = destPres->get_Masters();
// Clonar o slide mestre desejado da apresentação de origem para a coleção de mestres na
// Apresentação de destino
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Coleção de slides na apresentação de destino
auto slides = destPres->get_Slides();
// Clonar slide de origem para a coleção de slides de destino.
slides->AddClone(sourceSlide, iSlide, true);
// Salvar a apresentação de destino no disco
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterSlide](../../imasterslide/)
* Classe [MasterSlideCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)