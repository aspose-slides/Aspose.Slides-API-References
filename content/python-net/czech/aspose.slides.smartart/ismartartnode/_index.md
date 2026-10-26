---
title: ISmartArtNode class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode třída

Represents node of a SmartArt diagram.

The ISmartArtNode type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`child_nodes`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/child_nodes/) | Returns collections of all child nodes of current node.<br/> Pouze pro čtení [`ISmartArtNodeCollection`](/slides/python-net/cs/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/shapes/) | Returns collections of all shapes associated with the node.<br/> Pouze pro čtení [`ISmartArtShapeCollection`](/slides/python-net/cs/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/text_frame/) | Returns or sets text of the node.<br/> Pouze pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/is_assistant/) | Returns or sets the node as assistant.<br/> Čtení/zápis **bool**. |
| [`level`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/level/) | Returns nesting level of the node.<br/> Pouze pro čtení **int**. |
| [`bullet_fill_format`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | Returns the FillFormat object that contains fill formatting properties for a node bullet.<br/> Note: can return None for certain types of SmartArt layout which does not provide bullets for nodes.<br/> Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/position/) | Returns or sets zero-based position of the node among sibling nodes.<br/> Čtení/zápis **int**. |
| [`is_hidden`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/is_hidden/) | Returns true if this node is a hidden node in the data model.<br/> Pouze pro čtení **bool**. |
| [`organization_chart_layout`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | Returns or sets organization chart layout type associated with current node.<br/> Čtení/zápis [`OrganizationChartLayoutType`](/slides/python-net/cs/aspose.slides.smartart/organizationchartlayouttype). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`remove(self)`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode/remove/#) | Remove current node. |

### Viz také
* modul [`aspose.slides.smartart`](/slides/python-net/cs/aspose.slides.smartart)
* knihovna [`Aspose.Slides`](/slides/python-net)