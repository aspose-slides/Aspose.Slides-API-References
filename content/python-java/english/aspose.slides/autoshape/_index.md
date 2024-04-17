---
title: AutoShape
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/autoshape/
---

## AutoShape class

  Represents an AutoShape.
 
### addTextFrame {#addTextFrame}

| Name | Description |
| --- | --- |
| addTextFrame(String) | Adds a new TextFrame to a shape. If shape already has TextFrame then simply changes its text. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Default text for a new TextFrame. |

 **Returns:**
[TextFrame](../textframe)


---


### getAutoShapeLock {#getAutoShapeLock}

| Name | Description |
| --- | --- |
| getAutoShapeLock() | Returns autoshape's locks. Read-only IAutoShapeLock. |

 **Returns:**
[AutoShapeLock](../autoshapelock)


---


### getShapeLock {#getShapeLock}

| Name | Description |
| --- | --- |
| getShapeLock() | Returns shape's locks. Read-only IAutoShapeLock. |

 **Returns:**
[AutoShapeLock](../autoshapelock)


---


### getTextFrame {#getTextFrame}

| Name | Description |
| --- | --- |
| getTextFrame() | Returns TextFrame object for the AutoShape. Read-only ITextFrame. |

 **Returns:**
[TextFrame](../textframe)


---


### getUseBackgroundFill {#getUseBackgroundFill}

| Name | Description |
| --- | --- |
| getUseBackgroundFill() | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. Read/write boolean. |

 **Returns:**
boolean


---


### isTextBox {#isTextBox}

| Name | Description |
| --- | --- |
| isTextBox() | Specifies if the shape is a text box. If shape is not specified to be a text box does not mean that it cannot have text attached to it. A text box is merely a specialized shape with specific properties. |

 **Returns:**
boolean


---


### setUseBackgroundFill {#setUseBackgroundFill}

| Name | Description |
| --- | --- |
| setUseBackgroundFill(boolean) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. Read/write boolean. |


---


