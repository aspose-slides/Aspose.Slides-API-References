﻿---
title: ISmartArtNode class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.smartart/ismartartnode/
---


## ISmartArtNode class

Represents node of a SmartArt diagram.

The ISmartArtNode type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`child_nodes`](/slides/python-net/aspose.slides.smartart/ismartartnode/child_nodes/) | Returns collections of all child nodes of current node.<br/>            Read-only [`ISmartArtNodeCollection`](/slides/python-net/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/aspose.slides.smartart/ismartartnode/shapes/) | Returns collections of all shapes associated with the node.<br/>            Read-only [`ISmartArtShapeCollection`](/slides/python-net/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/aspose.slides.smartart/ismartartnode/text_frame/) | Returns or sets text of the node.<br/>            Read-only [`ITextFrame`](/slides/python-net/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/aspose.slides.smartart/ismartartnode/is_assistant/) | Returns or sets the node as assistant.<br/>            Read/write **bool**. |
| [`level`](/slides/python-net/aspose.slides.smartart/ismartartnode/level/) | Returns nesting level of the node.<br/>            Read-only **int**. |
| [`bullet_fill_format`](/slides/python-net/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | Returns the FillFormat object that contains fill formatting properties for a node bullet.<br/>            Note: can return None for certain types of SmartArt layout which does not provide bullets for nodes.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/aspose.slides.smartart/ismartartnode/position/) | Returns or sets zero-based position of the node among sibling nodes.<br/>            Read/write **int**. |
| [`is_hidden`](/slides/python-net/aspose.slides.smartart/ismartartnode/is_hidden/) | Returns true if this node is a hidden node in the data model.<br/>            Read-only **bool**. |
| [`organization_chart_layout`](/slides/python-net/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | Returns or sets organization chart layout type associated with current node.<br/>            Read/write [`OrganizationChartLayoutType`](/slides/python-net/aspose.slides.smartart/organizationchartlayouttype). |

## Methods

| Method | Description |
| :- | :- |
| [`remove`](/slides/python-net/aspose.slides.smartart/ismartartnode/remove/#) | Remove current node. |


### See Also
* module [`aspose.slides.smartart`](/slides/python-net/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)

