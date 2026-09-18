---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection classe

Representa uma coleção de todos os slides de layout na apresentação.
Estende a classe LayoutSlideCollection com métodos para adicionar/duplicar slides de layout no contexto da união das coleções individuais de slides de layout mestre.

**Herança:**[`GlobalLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/pt/aspose.slides/layoutslidecollection)

O tipo GlobalLayoutSlideCollection expõe os seguintes membros:

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | Adiciona uma cópia de um slide de layout especificado à apresentação. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | Adiciona uma cópia de um slide de layout especificado à apresentação. |
| [`get_by_type(self, type)`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | Retorna o primeiro slide de layout do tipo especificado.<br/>            Um tipo de slide de layout a ser encontrado.[`LayoutSlide`](/slides/python-net/pt/aspose.slides/layoutslide) com o tipo especificado ou None se nenhum layout for encontrado. |
| [`remove(self, value)`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | Remove um layout da coleção. |
| [`remove_unused(self)`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection/remove_unused/#) | Remove slides de layout não usados (slides de layout cujo HasDependingSlides é false). |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | Adiciona um novo slide de layout à apresentação. |

### Veja Também
* classe [`GlobalLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection)
* classe [`LayoutSlideCollection`](/slides/python-net/pt/aspose.slides/layoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)