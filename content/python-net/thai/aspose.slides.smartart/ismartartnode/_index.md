---
title: ISmartArtNode class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode คลาส

Represents node of a SmartArt diagram.

The ISmartArtNode type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`child_nodes`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/child_nodes/) | Returns collections of all child nodes of current node.<br/>            อ่านอย่างเดียว [`ISmartArtNodeCollection`](/slides/python-net/th/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/shapes/) | Returns collections of all shapes associated with the node.<br/>            อ่านอย่างเดียว [`ISmartArtShapeCollection`](/slides/python-net/th/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/text_frame/) | Returns or sets text of the node.<br/>            อ่านอย่างเดียว [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/is_assistant/) | Returns or sets the node as assistant.<br/>            อ่าน/เขียน **bool**. |
| [`level`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/level/) | Returns nesting level of the node.<br/>            อ่านอย่างเดียว **int**. |
| [`bullet_fill_format`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | Returns the FillFormat object that contains fill formatting properties for a node bullet.<br/>            Note: can return None for certain types of SmartArt layout which does not provide bullets for nodes.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/position/) | Returns or sets zero-based position of the node among sibling nodes.<br/>            อ่าน/เขียน **int**. |
| [`is_hidden`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/is_hidden/) | Returns true if this node is a hidden node in the data model.<br/>            อ่านอย่างเดียว **bool**. |
| [`organization_chart_layout`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | Returns or sets organization chart layout type associated with current node.<br/>            อ่าน/เขียน [`OrganizationChartLayoutType`](/slides/python-net/th/aspose.slides.smartart/organizationchartlayouttype). |

## วิธีการ

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/th/aspose.slides.smartart/ismartartnode/remove/#) | ลบโหนดปัจจุบัน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)