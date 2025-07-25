---
title: ISectionZoomFrame
second_title: Aspose.Slides for C++ API Reference
description: Represents a Section Zoom object in a slide.
type: docs
weight: 3602
url: /aspose.slides/isectionzoomframe/
---
## ISectionZoomFrame class


Represents a [Section](../section/) Zoom object in a slide.

```cpp
class ISectionZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Returns the alternative text associated with a shape. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Returns the title of alternative text associated with a shape. Read [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Property specifies how a shape will render in black-and-white display mode.. Read [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Returns the number of connection sites on the shape. Read-only **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Returns the shape's custom data. Read-only [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Returns the [EffectFormat](../effectformat/) object which contains pixel effects applied to a shape. Read-only [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Returns the [FillFormat](../fillformat/) object that contains fill formatting properties for a shape. Read-only [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Returns the shape frame's properties. Read [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Returns shape's locks. Read-only [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Gets the height of the shape, measured in points. Read **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Determines whether the shape is hidden. Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Returns the hyperlink defined for mouse click. Read [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks manager Read-only [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returns the hyperlink defined for mouse over. Read [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | Gets the image type of a zoom object. Read [ZoomImageType](../zoomimagetype/). Default value: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Gets 'Mark as decorative' option Reed/write **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Determines whether the shape is grouped. Read-only **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Determines whether the shape is TextHolder. Read-only **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Returns the [LineFormat](../lineformat/) object that contains line formatting properties for a shape. Read-only [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Returns the name of a shape. Read [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only **uint32_t**. See also [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Returns parent [GroupShape](../groupshape/) object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Returns the placeholder for a shape. Read-only [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Returns the presentation. Read-only [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Returns the raw shape frame's properties. Read [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | Gets the navigation behavior in slideshow. Read **bool**. Default value: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Returns the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Returns shape's locks. Read-only [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Gets value that specifies whether the Zoom will use the background of the destination slide. Read **bool**. Default value: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Returns the base slide. Read-only [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() | Gets the section object that the [Section](../section/) Zoom object is linked to. Read [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Returns the [ThreeDFormat](../threedformat/) object that contains line formatting properties for a shape. Read-only [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Gets the duration of the transition between Zoom and slide. Read **float**. Default value: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only **uint32_t**. See also [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Gets the width of the shape, measured in points. Read **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Gets the x-coordinate of the shape's upper-left corner, measured in points. Read **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Gets the y-coordinate of the shape's upper-left corner, measured in points. Read **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | Gets image for zoom object. Read [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type is used by default. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Returns shape thumbnail. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\> [GetThumbnail](../ishape/getthumbnail/)() | Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type is used by default. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\> [GetThumbnail](../ishape/getthumbnail/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Returns shape thumbnail. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Defines that this shape isn't a placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Sets the alternative text associated with a shape. Write [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Sets the title of alternative text associated with a shape. Write [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Property specifies how a shape will render in black-and-white display mode.. Write [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sets the shape frame's properties. Write [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Sets the height of the shape, measured in points. Write **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Determines whether the shape is hidden. Write **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sets the hyperlink defined for mouse click. Write [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sets the hyperlink defined for mouse over. Write [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Sets the image type of a zoom object. Write [ZoomImageType](../zoomimagetype/). Default value: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Sets 'Mark as decorative' option Reed/write **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Sets the name of a shape. Write [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sets the raw shape frame's properties. Write [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | Sets the navigation behavior in slideshow. Write **bool**. Default value: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Write **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Sets value that specifies whether the Zoom will use the background of the destination slide. Write **bool**. Default value: true |
| virtual void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | Sets the section object that the [Section](../section/) Zoom object is linked to. Write [ISection](../isection/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Sets the duration of the transition between Zoom and slide. Write **float**. Default value: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Sets the width of the shape, measured in points. Write **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Sets the x-coordinate of the shape's upper-left corner, measured in points. Write **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Sets the y-coordinate of the shape's upper-left corner, measured in points. Write **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Sets image for zoom object. Write [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Saves content of [Shape](../shape/) as SVG file. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Saves content of [Shape](../shape/) as SVG file. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [IZoomObject](../izoomobject/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)