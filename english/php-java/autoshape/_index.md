---
title: AutoShape
type: docs
weight: 0
url: /php-java/autoshape/
---

# AutoShape class

  Represents an AutoShape.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addTextFrame](/php-java/autoshape/addtextframe/)(String) | ITextFrame | Adds a new TextFrame to a shape. If shape already has TextFrame then simply changes its text. |
| [getAutoShapeLock](/php-java/autoshape/getautoshapelock/)() | IAutoShapeLock | Returns autoshape's locks. Read-only IAutoShapeLock. |
| [getShapeLock](/php-java/autoshape/getshapelock/)() | IAutoShapeLock | Returns shape's locks. Read-only IAutoShapeLock. |
| [getTextFrame](/php-java/autoshape/gettextframe/)() | ITextFrame | Returns TextFrame object for the AutoShape. Read-only ITextFrame. |
| [getUseBackgroundFill](/php-java/autoshape/getusebackgroundfill/)() | boolean | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. Read/write boolean. |
| [isTextBox](/php-java/autoshape/istextbox/)() | boolean | Specifies if the shape is a text box. If shape is not specified to be a text box does not mean that it cannot have text attached to it. A text box is merely a specialized shape with specific properties. |
| [setUseBackgroundFill](/php-java/autoshape/setusebackgroundfill/)(boolean) | void | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. Read/write boolean. |