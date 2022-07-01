---
title: Shape
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/shape/
---

## Shape class

  Represents a shape on a slide.
 

## Methods

| Name | Description |
| --- | --- |
| [addPlaceholder](addplaceholder)(Placeholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [getAlternativeText](getalternativetext)() | Returns or sets the alternative text associated with a shape. Read/write String. |
| [getAlternativeTextTitle](getalternativetexttitle)() | Returns or sets the title of alternative text associated with a shape. Read/write String. |
| [getBlackWhiteMode](getblackwhitemode)() | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |
| [getConnectionSiteCount](getconnectionsitecount)() | Returns the number of connection sites on the shape. Read-only int. |
| [getCustomData](getcustomdata)() | Returns the shape's custom data. Read-only ICustomData. |
| [getEffectFormat](geteffectformat)() | Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only IEffectFormat. |
| [getFillFormat](getfillformat)() | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only IFillFormat. |
| [getFrame](getframe)() | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |
| [getHeight](getheight)() | Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getHidden](gethidden)() | Determines whether the shape is hidden. Read/write boolean. |
| [getHyperlinkClick](gethyperlinkclick)() | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |
| [getHyperlinkManager](gethyperlinkmanager)() | Returns the hyperlink manager. Read-only IHyperlinkManager. |
| [getHyperlinkMouseOver](gethyperlinkmouseover)() | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |
| [getLineFormat](getlineformat)() | Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only ILineFormat. |
| [getName](getname)() | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |
| [getOfficeInteropShapeId](getofficeinteropshapeid)() | Gets unique shape identifier in slide scope. Read-only long. See also ( #getUniqueId) for getting unique shape identifier in presentation scope. |
| [getParentGroup](getparentgroup)() | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only IGroupShape. Property ( #isGrouped) determines whether the shape is grouped. |
| [getPlaceholder](getplaceholder)() | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only IPlaceholder. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a slide. Read-only IPresentation. |
| [getRawFrame](getrawframe)() | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |
| [getRotation](getrotation)() | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getShapeLock](getshapelock)() | Returns shape's locks. Read-only IBaseShapeLock. |
| [getSlide](getslide)() | Returns the parent slide of a shape. Read-only IBaseSlide. |
| [getThreeDFormat](getthreedformat)() | Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only IThreeDFormat. |
| [getThumbnail](getthumbnail)() | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [getThumbnail](getthumbnail)(int, float, float) | Returns shape thumbnail. |
| [getUniqueId](getuniqueid)() | Gets unique shape identifier in presentation scope. Read-only long. See also ( #getOfficeInteropShapeId) for getting unique shape identifier in slide scope. |
| [getWidth](getwidth)() | Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getX](getx)() | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getY](gety)() | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getZOrderPosition](getzorderposition)() | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only int. |
| [isGrouped](isgrouped)() | Determines whether the shape is grouped. Read-only boolean. Property ( #getParentGroup) returns parent GroupShape object if shape is grouped. |
| [isTextHolder](istextholder)() | Determines whether the shape is TextHolder_PPT. Read-only boolean. |
| [removePlaceholder](removeplaceholder)() | Defines that this shape isn't a placeholder. |
| [setAlternativeText](setalternativetext)(String) | Returns or sets the alternative text associated with a shape. Read/write String. |
| [setAlternativeTextTitle](setalternativetexttitle)(String) | Returns or sets the title of alternative text associated with a shape. Read/write String. |
| [setBlackWhiteMode](setblackwhitemode)(byte) | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |
| [setFrame](setframe)(ShapeFrame) | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |
| [setHeight](setheight)(float) | Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [setHidden](sethidden)(boolean) | Determines whether the shape is hidden. Read/write boolean. |
| [setHyperlinkClick](sethyperlinkclick)(Hyperlink) | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |
| [setHyperlinkMouseOver](sethyperlinkmouseover)(Hyperlink) | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |
| [setName](setname)(String) | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |
| [setRawFrame](setrawframe)(ShapeFrame) | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |
| [setRotation](setrotation)(float) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [setWidth](setwidth)(float) | Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [setX](setx)(float) | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [setY](sety)(float) | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [writeAsSvg](writeassvg)(OutputStream) | Saves content of Shape as SVG file. |
| [writeAsSvg](writeassvg)(OutputStream, SVGOptions) | Saves content of Shape as SVG file. |
