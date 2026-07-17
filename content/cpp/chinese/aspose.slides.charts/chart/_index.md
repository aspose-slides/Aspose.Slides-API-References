---
title: Chart
second_title: Aspose.Slides for C++ API 参考
description: 表示幻灯片上的图形图表。
type: docs
weight: 53
url: /zh/aspose.slides.charts/chart/
---
## Chart 类

表示幻灯片上的图形图表。

```cpp
class Chart : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::Charts::IChart
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | 如果不存在，则添加一个新占位符并将占位符属性设置为指定的占位符。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | 返回此图表的有效主题。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | 返回与形状关联的备用文本。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | 返回与形状关联的备用文本的标题。阅读 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() override | 提供对图表坐标轴的访问。只读 [IAxesManager](../iaxesmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() override | 返回一个对象，可更改 3D 图表后壁的格式。只读 [IChartWall](../ichartwall/)。 |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | 属性指定形状在黑白显示模式下的渲染方式。阅读 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() override | 返回与图表关联的链接或嵌入数据的信息。只读 [IChartData](../ichartdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() override | 返回图表的数据表。只读 [IDataTable](../idatatable/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() override | 返回图表标题。只读 [IChartTitle](../icharttitle/)。 |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | 返回形状的连接点数量。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | 返回形状的自定义数据。只读 [ICustomData](../../aspose.slides/icustomdata/)。 |
| [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() override | 返回在图表上绘制空白单元格的方式。阅读 [DisplayBlanksAsType](../displayblanksastype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | 返回包含应用于形状的像素效果的 [EffectFormat](../../aspose.slides/effectformat/) 对象。注意：对于某些没有效果属性的形状，可能返回 null。只读 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | 返回包含形状填充格式属性的 [FillFormat](../../aspose.slides/fillformat/) 对象。注意：对于某些没有填充属性的形状，可能返回 null。只读 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() override | 返回一个对象，可更改 3D 图表底部的格式。只读 [IChartWall](../ichartwall/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | 返回形状框架的属性。阅读 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | 返回形状的锁定状态。只读 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)。 |
| **bool** [get_HasDataTable](./get_hasdatatable/)() override | 确定图表是否具有数据表。读取 **bool**。 |
| **bool** [get_HasLegend](./get_haslegend/)() override | 确定图表是否具有图例。读取 **bool**。 |
| **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() override | 指定图表区域应具有圆角。读取 **bool**。 |
| **bool** [get_HasTitle](./get_hastitle/)() override | 确定图表是否具有可见标题。读取 **bool**。 |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | 获取形状的高度，单位为点。读取 **float**。 |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | 确定形状是否隐藏。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | 返回为鼠标点击定义的超链接。阅读 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | 返回超链接管理器。只读 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | 返回为鼠标悬停定义的超链接。阅读 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 获取“标记为装饰”选项。读取/写入 **bool**。 |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | 确定形状是否已分组。只读 **bool**。 |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | 确定形状是否为 TextHolder_PPT。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() override | 返回图表的图例。只读 [ILegend](../ilegend/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | 返回包含形状线条格式属性的 [LineFormat](../../aspose.slides/lineformat/) 对象。注意：对于某些没有线条属性的形状，可能返回 null。只读 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | 返回形状的名称。必须非空。如有需要可使用空字符串。阅读 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | 返回在幻灯片范围内唯一的标识符，该标识符在形状生命周期内保持不变，使 PowerPoint 或互操作代码能够在文档任何位置可靠地引用该形状。只读 **uint32_t**。另请参阅 [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | 如果形状已分组，则返回父 [GroupShape](../../aspose.slides/groupshape/) 对象；否则返回 null。只读 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() override | 表示图表的绘图区。只读 [IChartPlotArea](../ichartplotarea/)。 |
| **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() override | 确定是否仅绘制可见单元格。若为 false，则绘制可见和隐藏单元格。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | 返回幻灯片的父演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | 返回原始形状框架的属性。阅读 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | 返回指定形状绕 Z 轴旋转的角度（度）。正值表示顺时针旋转，负值表示逆时针旋转。读取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() override | 返回图表的 3D 旋转。只读 [IRotation3D](../irotation3d/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | 返回形状的锁定状态。只读 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() override | 指定在图表最大值上方显示数据标签。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() override | 返回一个对象，可更改 3D 图表侧壁的格式。只读 [IChartWall](../ichartwall/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | 返回形状的父幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| [StyleType](../styletype/) [get_Style](./get_style/)() override | 返回图表样式。阅读 [StyleType](../styletype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 返回图表文本格式。该属性不适用于以下类型：[ChartType::Treemap](../charttype/), [ChartType::Sunburst](../charttype/), [ChartType::Waterfall](../charttype/), [ChartType::Histogram](../charttype/), [ChartType::Funnel](../charttype/),[ChartType::BoxAndWhisker](../charttype/)。只读 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | 返回主题管理器。只读 [Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | 返回形状的 3D 效果属性的 [ThreeDFormat](../../aspose.slides/threedformat/) 对象。注意：对于某些没有 3D 属性的形状，可能返回 null。只读 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | 返回图表类型。阅读 [ChartType](../charttype/)。 |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | 返回内部的、演示文稿范围的标识符，供插件或其他代码使用。由于该值可能被用户或程序重新分配，不能视为持久唯一键。只读 **uint32_t**。另请参阅 [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() override | 指定绘制在图表之上的形状。只读 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | 获取形状的宽度，单位为点。读取 **float**。 |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | 获取形状左上角的 x 坐标，单位为点。读取 **float**。 |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | 获取形状左上角的 y 坐标，单位为点。读取 **float**。 |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | 返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最后面的形状，Shapes[Shapes.Count - 1] 返回最前面的形状。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状从其继承）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# 的 [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | 返回形状缩略图。默认使用 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 形状缩略图边界类型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | 返回形状缩略图。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | 获取根据渲染内容计算的形状可视边界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# 的 [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许为子类进行复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许为子类进行复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对 string 与 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | 定义此形状不是占位符。 |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | 设置与形状关联的备用文本。写入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 设置与形状关联的备用文本标题。写入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | 属性指定形状在黑白显示模式下的渲染方式。写入 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) override | 设置在图表上绘制空白单元格的方式。写入 [DisplayBlanksAsType](../displayblanksastype/)。 |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 设置形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_HasDataTable](./set_hasdatatable/)(**bool**) override | 确定图表是否具有数据表。写入 **bool**。 |
| void [set_HasLegend](./set_haslegend/)(**bool**) override | 确定图表是否具有图例。写入 **bool**。 |
| void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) override | 指定图表区域应具有圆角。写入 **bool**。 |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | 确定图表是否具有可见标题。写入 **bool**。 |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | 设置形状的高度，单位为点。写入 **float**。 |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | 确定形状是否隐藏。写入 **bool**。 |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | 设置为鼠标点击定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | 设置为鼠标悬停定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 设置“标记为装饰”选项。读取/写入 **bool**。 |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | 设置形状的名称。必须非空。如有需要可使用空字符串。写入 [System::String](../../system/string/)。 |
| void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) override | 确定是否仅绘制可见单元格。若为 false，则绘制可见和隐藏单元格。写入 **bool**。 |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 设置原始形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | 设置指定形状绕 Z 轴旋转的角度（度）。正值表示顺时针旋转，负值表示逆时针旋转。写入 **float**。 |
| void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) override | 指定在图表最大值上方显示数据标签。写入 **bool**。 |
| void [set_Style](./set_style/)([StyleType](../styletype/)) override | 设置图表样式。写入 [StyleType](../styletype/)。 |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | 设置图表类型。写入 [ChartType](../charttype/)。 |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | 设置形状的宽度，单位为点。写入 **float**。 |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | 设置形状左上角的 x 坐标，单位为点。写入 **float**。 |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | 设置形状左上角的 y 坐标，单位为点。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# 的 [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| void [ValidateChartLayout](./validatechartlayout/)() override | 计算图表元素的实际值。实际值包括实现 [IActualLayout](../iactuallayout/) 接口的元素位置（[IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)）以及实际坐标轴数值（[IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)）。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 将 [Shape](../../aspose.slides/shape/) 的内容保存为 SVG 文件。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 将 [Shape](../../aspose.slides/shape/) 的内容保存为 SVG 文件。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [GraphicalObject](../../aspose.slides/graphicalobject/)
* 类 [IChart](../ichart/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)