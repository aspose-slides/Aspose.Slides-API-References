---
title: Table
second_title: Aspose.Slides for C++ API Reference
description: Represents a table on a slide.
type: docs
weight: 5149
url: /aspose.slides/table/
---
## Table class


Represents a table on a slide.

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Returns the alternative text associated with a shape. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Returns the title of alternative text associated with a shape. Read [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Property specifies how a shape will render in black-and-white display mode.. Read [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | Returns a column at the specified index. Read-only [Aspose::Slides::IColumn](../icolumn/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | Returns the collectoin of columns. Read-only [IColumnCollection](../icolumncollection/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Returns the number of connection sites on the shape. Read-only **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Returns the shape's custom data. Read-only [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Returns the [EffectFormat](../effectformat/) object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Returns the [FillFormat](../fillformat/) object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only [IFillFormat](../ifillformat/). |
| **bool** [get_FirstCol](./get_firstcol/)() override | Determines whether the first column of a table has to be drawn with a special formatting. Read **bool**. |
| **bool** [get_FirstRow](./get_firstrow/)() override | Determines whether the first row of a table has to be drawn with a special formatting. Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Returns the shape frame's properties. Read [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Returns shape's locks. Read-only [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Returns the height of the shape. Read **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determines whether the shape is hidden. Read **bool**. |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | Determines whether the even rows has to be drawn with a different formatting. Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Returns the hyperlink defined for mouse click. Read [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Returns the hyperlink manager. Read-only [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Returns the hyperlink defined for mouse over. Read [IHyperlink](../ihyperlink/). |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determines whether the shape is grouped. Read-only **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determines whether the shape is TextHolder_PPT. Read-only **bool**. |
| **bool** [get_LastCol](./get_lastcol/)() override | Determines whether the last column of a table has to be drawn with a special formatting. Read **bool**. |
| **bool** [get_LastRow](./get_lastrow/)() override | Determines whether the last row of a table has to be drawn with a special formatting. Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Returns the [LineFormat](../lineformat/) object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Returns the name of a shape. Must be not null. Use empty string value if needed. Read [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Gets unique shape identifier in slide scope. Read-only **uint32_t**. See also [Shape::get_UniqueId](../shape/get_uniqueid/) for getting unique shape identifier in presentation scope. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Returns parent [GroupShape](../groupshape/) object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Returns the parent presentation of a slide. Read-only [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Returns the raw shape frame's properties. Read [IShapeFrame](../ishapeframe/). |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | Determines whether the table has right to left reading order. Reads **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Returns the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | Returns a row at the specified index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | Returns the collectoin of rows. Read-only [IRowCollection](../irowcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Returns shape's locks. Read-only [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Returns the parent slide of a shape. Read-only [IBaseSlide](../ibaseslide/). |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | Gets builtin table style. Read [TableStylePreset](../tablestylepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | Returns the [TableFormat](../tableformat/) object that contains formatting properties for this table. Read-only [ITableFormat](../itableformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Returns the [ThreeDFormat](../threedformat/) object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Gets unique shape identifier in presentation scope. Read-only **uint32_t**. See also [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) for getting unique shape identifier in slide scope. |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | Determines whether the even columns has to be drawn with a different formatting. Read **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Returns the width of the shape. Read **float**. |
| **float** [get_X](../shape/get_x/)() override | Returns the x-coordinate of the upper-left corner of the shape. Read **float**. |
| **float** [get_Y](../shape/get_y/)() override | Returns the y-coordinate of the upper-left corner of the shape. Read **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\> [GetThumbnail](../shape/getthumbnail/)() override | Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type is used by default. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\> [GetThumbnail](../shape/getthumbnail/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Returns shape thumbnail. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | Returns the cell at the specified column and row indexes. Read-only [Cell](../cell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | Merges neighbour cells. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Defines that this shape isn't a placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Sets the alternative text associated with a shape. Write [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Sets the title of alternative text associated with a shape. Write [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Property specifies how a shape will render in black-and-white display mode.. Write [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | Determines whether the first column of a table has to be drawn with a special formatting. Write **bool**. |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | Determines whether the first row of a table has to be drawn with a special formatting. Write **bool**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Sets the shape frame's properties. Write [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Sets the height of the shape. Write **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Determines whether the shape is hidden. Write **bool**. |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | Determines whether the even rows has to be drawn with a different formatting. Write **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Sets the hyperlink defined for mouse click. Write [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Sets the hyperlink defined for mouse over. Write [IHyperlink](../ihyperlink/). |
| void [set_LastCol](./set_lastcol/)(**bool**) override | Determines whether the last column of a table has to be drawn with a special formatting. Write **bool**. |
| void [set_LastRow](./set_lastrow/)(**bool**) override | Determines whether the last row of a table has to be drawn with a special formatting. Write **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Sets the name of a shape. Must be not null. Use empty string value if needed. Write [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Sets the raw shape frame's properties. Write [IShapeFrame](../ishapeframe/). |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | Determines whether the table has right to left reading order. Writes **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Write **float**. |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | Sets builtin table style. Write [TableStylePreset](../tablestylepreset/). |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | Determines whether the even columns has to be drawn with a different formatting. Write **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Sets the width of the shape. Write **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Sets the x-coordinate of the upper-left corner of the shape. Write **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Sets the y-coordinate of the upper-left corner of the shape. Write **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | Sets defined portion format properties to all table cells' portions. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | Sets defined paragraph format properties to all table cells' paragraphs. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | Sets defined text frame format properties to all table cells' text frames. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Saves content of [Shape](../shape/) as SVG file. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Saves content of [Shape](../shape/) as SVG file. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [GraphicalObject](../graphicalobject/)
* Class [ITable](../itable/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)