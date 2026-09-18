---
title: MasterLayoutSlideCollection class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection classe

Representa uma coleção de todos os slides de layout do slide mestre definido.  
Estende a classe LayoutSlideCollection com métodos para adicionar/inserir/remover/clonar/reordenar slides de layout no contexto das coleções individuais de slides de layout do mestre.

**Herança:**[`MasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/pt/aspose.slides/layoutslidecollection)

O tipo MasterLayoutSlideCollection expõe os seguintes membros:

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Retorna o primeiro slide de layout do tipo especificado.<br/>            Um tipo de slide de layout a ser encontrado.[`LayoutSlide`](/slides/python-net/pt/aspose.slides/layoutslide) com o tipo especificado ou None se nenhum layout for encontrado. |
| [`remove(self, value)`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Remove um layout da coleção. |
| [`remove_unused(self)`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Remove slides de layout não usados (slides de layout cujo HasDependingSlides é false). |
| [`add_clone(self, source_layout)`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Adiciona uma cópia de um slide de layout especificado ao final da coleção. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Insere uma cópia de um slide de layout especificado na posição especificada da coleção. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Adiciona um novo slide de layout ao final da coleção. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Insere um novo slide de layout na posição especificada da coleção. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Remove o elemento no índice especificado da coleção. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Move o slide de layout da coleção para a posição especificada. |

### Ver também
* classe [`LayoutSlideCollection`](/slides/python-net/pt/aspose.slides/layoutslidecollection)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)