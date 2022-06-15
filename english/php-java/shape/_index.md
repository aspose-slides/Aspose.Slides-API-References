---
title: Shape
type: docs
weight: 0
url: /php-java/shape/
---

# Shape class

  Represents a shape on a slide.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addPlaceholder](/php-java/shape/addplaceholder/)(IPlaceholder) | IPlaceholder | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [getAlternativeText](/php-java/shape/getalternativetext/)() | String | Returns or sets the alternative text associated with a shape. Read/write String. |
| [getAlternativeTextTitle](/php-java/shape/getalternativetexttitle/)() | String | Returns or sets the title of alternative text associated with a shape. Read/write String. |
| [getBlackWhiteMode](/php-java/shape/getblackwhitemode/)() | byte | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |
| [getConnectionSiteCount](/php-java/shape/getconnectionsitecount/)() | int | Returns the number of connection sites on the shape. Read-only int. |
| [getCustomData](/php-java/shape/getcustomdata/)() | ICustomData | Returns the shape's custom data. Read-only ICustomData. |
| [getEffectFormat](/php-java/shape/geteffectformat/)() | IEffectFormat | Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only IEffectFormat. |
| [getFillFormat](/php-java/shape/getfillformat/)() | IFillFormat | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only IFillFormat. |
| [getFrame](/php-java/shape/getframe/)() | IShapeFrame | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |
| [getHeight](/php-java/shape/getheight/)() | float | Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getHidden](/php-java/shape/gethidden/)() | boolean | Determines whether the shape is hidden. Read/write boolean. |
| [getHyperlinkClick](/php-java/shape/gethyperlinkclick/)() | IHyperlink | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |
| [getHyperlinkManager](/php-java/shape/gethyperlinkmanager/)() | IHyperlinkManager | Returns the hyperlink manager. Read-only IHyperlinkManager. |
| [getHyperlinkMouseOver](/php-java/shape/gethyperlinkmouseover/)() | IHyperlink | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |
| [getLineFormat](/php-java/shape/getlineformat/)() | ILineFormat | Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only ILineFormat. |
| [getName](/php-java/shape/getname/)() | String | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |
| [getOfficeInteropShapeId](/php-java/shape/getofficeinteropshapeid/)() | long | Gets unique shape identifier in slide scope. Read-only long. See also ( #getUniqueId) for getting unique shape identifier in presentation scope. |
| [getParentGroup](/php-java/shape/getparentgroup/)() | IGroupShape | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only IGroupShape. Property ( #isGrouped) determines whether the shape is grouped. |
| [getPlaceholder](/php-java/shape/getplaceholder/)() | IPlaceholder | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only IPlaceholder. |
| [getPresentation](/php-java/shape/getpresentation/)() | IPresentation | Returns the parent presentation of a slide. Read-only IPresentation. |
| [getRawFrame](/php-java/shape/getrawframe/)() | IShapeFrame | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |
| [getRotation](/php-java/shape/getrotation/)() | float | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getShapeLock](/php-java/shape/getshapelock/)() | IBaseShapeLock | Returns shape's locks. Read-only IBaseShapeLock. |
| [getSlide](/php-java/shape/getslide/)() | IBaseSlide | Returns the parent slide of a shape. Read-only IBaseSlide. |
| [getThreeDFormat](/php-java/shape/getthreedformat/)() | IThreeDFormat | Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only IThreeDFormat. |
| [getThumbnail](/php-java/shape/getthumbnail/)() | BufferedImage | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [getThumbnail](/php-java/shape/getthumbnail/)(int, float, float) | BufferedImage | Returns shape thumbnail. |
| [getUniqueId](/php-java/shape/getuniqueid/)() | long | Gets unique shape identifier in presentation scope. Read-only long. See also ( #getOfficeInteropShapeId) for getting unique shape identifier in slide scope. |
| [getWidth](/php-java/shape/getwidth/)() | float | Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getX](/php-java/shape/getx/)() | float | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getY](/php-java/shape/gety/)() | float | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [getZOrderPosition](/php-java/shape/getzorderposition/)() | int | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only int. |
| [isGrouped](/php-java/shape/isgrouped/)() | boolean | Determines whether the shape is grouped. Read-only boolean. Property ( #getParentGroup) returns parent GroupShape object if shape is grouped. |
| [isTextHolder](/php-java/shape/istextholder/)() | boolean | Determines whether the shape is TextHolder_PPT. Read-only boolean. |
| [removePlaceholder](/php-java/shape/removeplaceholder/)() | void | Defines that this shape isn't a placeholder. |
| [setAlternativeText](/php-java/shape/setalternativetext/)(String) | void | Returns or sets the alternative text associated with a shape. Read/write String. |
| [setAlternativeTextTitle](/php-java/shape/setalternativetexttitle/)(String) | void | Returns or sets the title of alternative text associated with a shape. Read/write String. |
| [setBlackWhiteMode](/php-java/shape/setblackwhitemode/)(byte) | void | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |
| [setFrame](/php-java/shape/setframe/)(IShapeFrame) | void | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |
| [setHeight](/php-java/shape/setheight/)(float) | void | Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [setHidden](/php-java/shape/sethidden/)(boolean) | void | Determines whether the shape is hidden. Read/write boolean. |
| [setHyperlinkClick](/php-java/shape/sethyperlinkclick/)(IHyperlink) | void | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |
| [setHyperlinkMouseOver](/php-java/shape/sethyperlinkmouseover/)(IHyperlink) | void | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |
| [setName](/php-java/shape/setname/)(String) | void | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |
| [setRawFrame](/php-java/shape/setrawframe/)(IShapeFrame) | void | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |
| [setRotation](/php-java/shape/setrotation/)(float) | void | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [setWidth](/php-java/shape/setwidth/)(float) | void | Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [setX](/php-java/shape/setx/)(float) | void | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [setY](/php-java/shape/sety/)(float) | void | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |
| [writeAsSvg](/php-java/shape/writeassvg/)(OutputStream) | void | Saves content of Shape as SVG file. |
| [writeAsSvg](/php-java/shape/writeassvg/)(OutputStream, ISVGOptions) | void | Saves content of Shape as SVG file. |
