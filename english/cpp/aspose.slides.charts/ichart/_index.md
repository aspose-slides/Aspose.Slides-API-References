---
title: IChart
second_title: Aspose.Slides for C++ API Reference
description: Represents an graphic chart on a slide.
type: docs
weight: 573
url: /cpp/aspose.slides.charts/ichart/
---
## IChart class


Represents an graphic chart on a slide.

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Returns an effective theme for this themeable object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Returns the alternative text associated with a shape. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Returns the title of alternative text associated with a shape. Read [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | Provide access to chart axes. Read-only [IAxesManager](../iaxesmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | Returns an object which allows to change format of the back wall of a 3D chart. Read-only [IChartWall](../ichartwall/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Property specifies how a shape will render in black-and-white display mode.. Read [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | Returns the chart. Read-only [IChart](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | Returns information about the linked or embedded data associated with a chart. Read-only [IChartData](../ichartdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | Returns a data table of a chart. Read-only [IDataTable](../idatatable/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | Returns a chart title Read-only [IChartTitle](../icharttitle/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Returns the number of connection sites on the shape. Read-only **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Returns the shape's custom data. Read-only [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | Returns the way to plot blank cells on a chart. Read [DisplayBlanksAsType](../displayblanksastype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Returns the [EffectFormat](../../aspose.slides/effectformat/) object which contains pixel effects applied to a shape. Read-only [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Returns the [FillFormat](../../aspose.slides/fillformat/) object that contains fill formatting properties for a shape. Read-only [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | Returns an object which allows to change format of the floor of a 3D chart. Read-only [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Returns the shape frame's properties. Read [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | Returns shape's locks. Read-only [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | Determines whether a chart has a data table. Read **bool**. |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | Determines whether a chart has a legend. Read **bool**. |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | Specifies the chart area shall have rounded corners. Read **bool**. |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Determines whether a chart has a visible title. Read **bool**. |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Returns the height of the shape. Read **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Determines whether the shape is hidden. Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Returns the hyperlink defined for mouse click. Read [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks manager Read-only [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returns the hyperlink defined for mouse over. Read [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Determines whether the shape is grouped. Read-only **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Determines whether the shape is TextHolder. Read-only **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | Returns a legend for a chart. Read-only [ILegend](../ilegend/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Returns the [LineFormat](../../aspose.slides/lineformat/) object that contains line formatting properties for a shape. Read-only [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Returns the name of a shape. Read [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Gets unique shape identifier in slide scope. Read-only **uint32_t**. See also [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/) for getting unique shape identifier in presentation scope. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Returns parent [GroupShape](../../aspose.slides/groupshape/) object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Returns the placeholder for a shape. Read-only [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | Represents the plot area of a chart. Read-only [IChartPlotArea](../ichartplotarea/). |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returns the presentation. Read-only [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Returns the raw shape frame's properties. Read [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Returns the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | Returns a 3D rotation of a chart. Read-only [IRotation3D](../irotation3d/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Returns shape's locks. Read-only [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | Specifies data labels over the maximum of the chart shall be shown. Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | Returns an object which allows to change format of the side wall of a 3D chart. Read-only [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returns the base slide. Read-only [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | Returns the chart style. Read [StyleType](../styletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Returns chart text format. Read-only [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | Returns override theme manager. Read-only [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Returns the [ThreeDFormat](../../aspose.slides/threedformat/) object that contains line formatting properties for a shape. Read-only [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | Returns the chart type. Read [ChartType](../charttype/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Gets unique shape identifier in presentation scope. Read-only **uint32_t**. See also [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/) for getting unique shape identifier in slide scope. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | Specify the shapes drawn on top of the chart. Read-only [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Returns the width of the shape. Read **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Returns the x-coordinate of the upper-left corner of the shape. Read **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Returns the y-coordinate of the upper-left corner of the shape. Read **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\> [GetThumbnail](../../aspose.slides/ishape/getthumbnail/)() | Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) shape thumbnail bounds type is used by default. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\> [GetThumbnail](../../aspose.slides/ishape/getthumbnail/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Returns shape thumbnail. |
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
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Defines that this shape isn't a placeholder. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Sets the alternative text associated with a shape. Write [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Sets the title of alternative text associated with a shape. Write [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Property specifies how a shape will render in black-and-white display mode.. Write [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | Sets the way to plot blank cells on a chart. Write [DisplayBlanksAsType](../displayblanksastype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Sets the shape frame's properties. Write [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | Determines whether a chart has a data table. Write **bool**. |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | Determines whether a chart has a legend. Write **bool**. |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | Specifies the chart area shall have rounded corners. Write **bool**. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Determines whether a chart has a visible title. Write **bool**. |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Sets the height of the shape. Write **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Determines whether the shape is hidden. Write **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Sets the hyperlink defined for mouse click. Write [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Sets the hyperlink defined for mouse over. Write [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Sets the name of a shape. Write [System::String](../../system/string/). |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Write **bool**. |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Sets the raw shape frame's properties. Write [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Write **float**. |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | Specifies data labels over the maximum of the chart shall be shown. Write **bool**. |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | Sets the chart style. Write [StyleType](../styletype/). |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | Sets the chart type. Write [ChartType](../charttype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Sets the width of the shape. Write **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Sets the x-coordinate of the upper-left corner of the shape. Write **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Sets the y-coordinate of the upper-left corner of the shape. Write **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | Calculates actual values of chart elements. Actual values inlude position of elements that implement [IActualLayout](../iactuallayout/) interface ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) and actual axes values ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Saves content of [Shape](../../aspose.slides/shape/) as SVG file. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Saves content of [Shape](../../aspose.slides/shape/) as SVG file. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* Class [IFormattedTextContainer](../iformattedtextcontainer/)
* Class [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)