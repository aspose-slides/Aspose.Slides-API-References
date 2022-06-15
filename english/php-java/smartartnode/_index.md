---
title: SmartArtNode
type: docs
weight: 0
url: /php-java/smartartnode/
---

# SmartArtNode class

 Represents node of a SmartArt object
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBulletFillFormat](/slides/php-java/smartartnode/getbulletfillformat/)() | IFillFormat | Returns the FillFormat object that contains fill formatting properties for a node bullet. Note: can return null for certain types of SmartArt layout which does not provide bullets for nodes. Read-only IFillFormat. |
| [getChildNodes](/slides/php-java/smartartnode/getchildnodes/)() | ISmartArtNodeCollection | Returns collections of all child nodes of the current node. Read-only ISmartArtNodeCollection. |
| [getLevel](/slides/php-java/smartartnode/getlevel/)() | int | Returns nesting level of the node. Read-only int. |
| [getOrganizationChartLayout](/slides/php-java/smartartnode/getorganizationchartlayout/)() | int | Returns or sets organization chart layout type associated with current node. Read/write OrganizationChartLayoutType. |
| [getPosition](/slides/php-java/smartartnode/getposition/)() | int | Returns or sets zero-based position of node among sibling nodes. Read/write int. |
| [getShapes](/slides/php-java/smartartnode/getshapes/)() | ISmartArtShapeCollection | Returns collections of all shapes associated with the node. Read-only ISmartArtShapeCollection. |
| [getTextFrame](/slides/php-java/smartartnode/gettextframe/)() | ITextFrame | Returns or sets text of the node. Read-only ITextFrame. |
| [isAssistant](/slides/php-java/smartartnode/isassistant/)() | boolean | Returns or sets the node as assistant. Read/write boolean. |
| [isHidden](/slides/php-java/smartartnode/ishidden/)() | boolean | Returns true if this node is a hidden node in the data model. Read-only boolean. |
| [remove](/slides/php-java/smartartnode/remove/)() | boolean | Remove current node. |
| [setAssistant](/slides/php-java/smartartnode/setassistant/)(boolean) | void | Returns or sets the node as assistant. Read/write boolean. |
| [setOrganizationChartLayout](/slides/php-java/smartartnode/setorganizationchartlayout/)(int) | void | Returns or sets organization chart layout type associated with current node. Read/write OrganizationChartLayoutType. |
| [setPosition](/slides/php-java/smartartnode/setposition/)(int) | void | Returns or sets zero-based position of node among sibling nodes. Read/write int. |
