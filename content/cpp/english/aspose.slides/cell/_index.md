---
title: Cell
second_title: Aspose.Slides for C++ API Reference
description: Represents a cell of a table.
type: docs
weight: 274
url: /aspose.slides/cell/
---
## Cell class


Represents a cell of a table.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Determines whether or not text box centered inside a cell. Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Returns the [CellFormat](../cellformat/) object that contains formatting properties for this cell. Read-only [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Returns the number of grid columns in the parent table's table grid which shall be spanned by the current cell. This property allows cells to have the appearance of being merged, as they span vertical boundaries of other cells in the table. Read-only **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Gets first column of cell. Read-only [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Returns an index of first column, covered by the cell. Read-only **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Gets first row of cell. Read-only [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Returns an index of first row, covered by the cell. Read-only **int32_t**. |
| **double** [get_Height](./get_height/)() override | Returns the height of the cell. Read-only **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Returns true if the cell is merged with any adjusted cell, false otherwise. Read-only **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Returns the bottom margin in a [TextFrame](../textframe/). Read **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Returns the left margin in a [TextFrame](../textframe/). Read **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Returns the right margin in a [TextFrame](../textframe/). Read **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Returns the top margin in a [TextFrame](../textframe/). Read **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Returns the minimum height of a cell. This is a sum of minimal heights of all rows cowered by the cell. Read-only **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Returns a distance from left side of a table to left side of a cell. Read-only **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Returns a distance from top side of a table to top side of a cell. Read-only **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Returns the parent presentation of a cell. Read-only [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Returns the number of rows that a merged cell spans. This is used in combination with the vMerge attribute on other cells in order to specify the beginning cell of a horizontal merge. Read-only **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Returns the parent slide of a cell. Read-only [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Returns the parent [Table](../table/) object for a cell. Read-only [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Returns the text anchor type. Read [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Returns the text frame of a cell. Read-only [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Returns the type of vertical text. Read [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Returns the width of the cell. Read-only **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
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
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Determines whether or not text box centered inside a cell. Write **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Sets the bottom margin in a [TextFrame](../textframe/). Write **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Sets the left margin in a [TextFrame](../textframe/). Write **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Sets the right margin in a [TextFrame](../textframe/). Write **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Sets the top margin in a [TextFrame](../textframe/). Write **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Sets the text anchor type. Write [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Sets the type of vertical text. Write [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Splits the cell to two cells by index of column. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Splits the cell by height. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Splits the cell to two cells by index of row. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Splits the cell by width. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [IDOMObject](../idomobject/)
* Class [ICell](../icell/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)