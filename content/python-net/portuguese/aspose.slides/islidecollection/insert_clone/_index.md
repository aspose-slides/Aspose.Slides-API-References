---
title: insert_clone method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Insere uma cópia de um slide especificado na posição especificada da coleção.

### Retorno

Slide inserido.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Índice do novo slide. |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide a ser clonado. |

### Observações

Ao clonar um slide entre apresentações diferentes, o mestre do slide também pode ser clonado.  
Um registro interno é usado para rastrear mestres clonados automaticamente, a fim de evitar a criação de múltiplos clones do mesmo slide mestre.  
A clonagem manual de slides mestres não será impedida nem registrada.  
Se precisar de mais controle sobre o processo de clonagem, use  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** ou  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** para clonar slides e  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** para clonar mestres.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Insere uma cópia de um slide especificado na posição especificada da coleção.

### Retorno

Slide inserido.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Índice do novo slide. |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide a ser clonado. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide) | Slide de layout para o novo slide. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Insere uma cópia de um slide fonte especificado na posição especificada da coleção.  
O layout apropriado será selecionado automaticamente a partir do mestre especificado (o layout apropriado é o layout com o mesmo Tipo ou Nome que o layout do slide de origem). Se não houver layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false).

### Retorno

Slide inserido.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Índice do novo slide. |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide a ser clonado. |
| dest_master | [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide) | Slide mestre para o novo slide. |
| allow_clone_missing_layout | **bool** | Se não houver layout apropriado no mestre especificado, então o layout do <br/><br/>slide de origem será clonado (se allowCloneMissingLayout for true) ou <br/><br/>PptxEditException será lançada (se allowCloneMissingLayout for false). |

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se não houver layout apropriado no mestre especificado e <br/>allowCloneMissingLayout for false. |



### Veja Também
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide)
* classe [`ISlide`](/slides/python-net/pt/aspose.slides/islide)
* classe [`ISlideCollection`](/slides/python-net/pt/aspose.slides/islidecollection)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)