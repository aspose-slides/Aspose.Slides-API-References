---
title: IChart
second_title: Aspose.Slides 的 C++ API 参考
description: 表示幻灯片上的图形图表。
type: docs
weight: 573
url: /zh/aspose.slides.charts/ichart/
---
## IChart 类

表示幻灯片上的图形图表。

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | 如果不存在则添加新的占位符，并将占位符属性设置为指定的占位符。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | 返回此可设主题对象的有效主题。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | 返回与形状关联的替代文本。请参阅 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | 返回与形状关联的替代文本标题。请参阅 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | 提供对图表轴的访问。只读 [IAxesManager](../iaxesmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | 返回一个对象，可更改 3D 图表背墙的格式。只读 [IChartWall](../ichartwall/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | 属性指定形状在黑白显示模式下的渲染方式。请参阅 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回图表。只读 [IChart](./)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | 返回与图表关联的链接或嵌入数据的信息。只读 [IChartData](../ichartdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | 返回图表的数据表。只读 [IDataTable](../idatatable/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | 返回图表标题。只读 [IChartTitle](../icharttitle/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | 返回形状的连接点数量。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | 返回形状的自定义数据。只读 [ICustomData](../../aspose.slides/icustomdata/)。 |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | 返回在图表上绘制空白单元格的方式。请参阅 [DisplayBlanksAsType](../displayblanksastype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | 返回包含应用于形状的像素效果的 [EffectFormat](../../aspose.slides/effectformat/) 对象。只读 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | 返回包含形状填充格式属性的 [FillFormat](../../aspose.slides/fillformat/) 对象。只读 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | 返回一个对象，可更改 3D 图表底部的格式。只读 [IChartWall](../ichartwall/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | 返回形状框架的属性。请参阅 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | 返回形状的锁定设置。只读 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)。 |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | 确定图表是否有数据表。只读 **bool**。 |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | 确定图表是否有图例。只读 **bool**。 |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | 指定图表区域应具有圆角。只读 **bool**。 |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | 确定图表是否有可见标题。只读 **bool**。 |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | 获取形状的高度，单位为点。只读 **float**。 |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | 确定形状是否隐藏。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | 返回鼠标单击时定义的超链接。请参阅 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | 超链接管理器。只读 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | 返回鼠标悬停时定义的超链接。请参阅 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | 获取“标记为装饰性”选项。读/写 **bool**。 |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | 确定形状是否已分组。只读 **bool**。 |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | 确定形状是否为 TextHolder。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | 返回图表的图例。只读 [ILegend](../ilegend/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | 返回包含形状线条格式属性的 [LineFormat](../../aspose.slides/lineformat/) 对象。只读 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | 返回形状的名称。请参阅 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | 返回一个针对幻灯片范围的唯一标识符，在形状的整个生命周期内保持不变，并允许 PowerPoint 或互操作代码在文档的任何位置可靠地引用该形状。只读 **uint32_t**。另见 [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | 如果形状已分组，则返回父 [GroupShape](../../aspose.slides/groupshape/) 对象。否则返回 null。只读 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | 返回形状的占位符。只读 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | 表示图表的绘图区。只读 [IChartPlotArea](../ichartplotarea/)。 |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | 确定是否仅绘制可见单元格。若为 false，则绘制可见和隐藏的单元格。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | 返回原始形状框架的属性。请参阅 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | 返回指定形状围绕 z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。只读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | 返回图表的 3D 旋转。只读 [IRotation3D](../irotation3d/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | 返回形状的锁定设置。只读 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | 指定应显示图表最大值以上的数据标签。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | 返回一个对象，可更改 3D 图表侧墙的格式。只读 [IChartWall](../ichartwall/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | 返回图表样式。请参阅 [StyleType](../styletype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 返回图表文本格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | 返回覆盖主题管理器。只读 [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | 返回包含形状线条格式属性的 [ThreeDFormat](../../aspose.slides/threedformat/) 对象。只读 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | 返回图表类型。请参阅 [ChartType](../charttype/)。 |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | 返回一个内部的、针对演示文稿范围的标识符，供插件或其他代码使用。由于此值可能被用户或程序重新分配，不能被视为持久的唯一键。只读 **uint32_t**。另见 [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | 指定绘制在图表上方的形状。只读 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | 获取形状的宽度，单位为点。只读 **float**。 |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | 获取形状左上角的 x 坐标，单位为点。只读 **float**。 |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | 获取形状左上角的 y 坐标，单位为点。只读 **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | 返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最底部的形状，Shapes[Shapes.Count - 1] 返回最前面的形状。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | 返回基本占位符形状（来自布局和/或母版幻灯片且当前形状继承自该形状的形状）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的散列。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | 返回形状缩略图。默认使用 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 形状缩略图边界类型。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | 返回形状缩略图。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上并不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上并不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | 定义此形状不是占位符。 |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | 设置与形状关联的替代文本。写入 [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 设置与形状关联的替代文本标题。写入 [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | 属性指定形状在黑白显示模式下的渲染方式。写入 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | 设置在图表上绘制空白单元格的方式。写入 [DisplayBlanksAsType](../displayblanksastype/)。 |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 设置形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | 确定图表是否有数据表。写入 **bool**。 |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | 确定图表是否有图例。写入 **bool**。 |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | 指定图表区域应具有圆角。写入 **bool**。 |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | 确定图表是否有可见标题。写入 **bool**。 |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | 设置形状的高度，单位为点。写入 **float**。 |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | 确定形状是否隐藏。写入 **bool**。 |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 设置鼠标单击时定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 设置鼠标悬停时定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | 设置“标记为装饰性”选项。读/写 **bool**。 |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | 设置形状的名称。写入 [System::String](../../system/string/)。 |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | 确定是否仅绘制可见单元格。若为 false，则绘制可见和隐藏的单元格。写入 **bool**。 |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 设置原始形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | 设置指定形状围绕 z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。写入 **float**。 |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | 指定应显示图表最大值以上的数据标签。写入 **bool**。 |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | 设置图表样式。写入 [StyleType](../styletype/)。 |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | 设置图表类型。写入 [ChartType](../charttype/)。 |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | 设置形状的宽度，单位为点。写入 **float**。 |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | 设置形状左上角的 x 坐标，单位为点。写入 **float**。 |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | 设置形状左上角的 y 坐标，单位为点。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中切换指针为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | 计算图表元素的实际值。实际值包括实现 [IActualLayout](../iactuallayout/) 接口的元素位置（[IActualLayout::get_ActualX](../iactuallayout/get_actualx/)、[IActualLayout::get_ActualY](../iactuallayout/get_actualy/)、[IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/)、[IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)）以及实际轴值（[IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/)、[IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/)、[IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/)、[IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/)、[IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/)、[IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)）。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | 将 [Shape](../../aspose.slides/shape/) 内容保存为 SVG 文件。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 将 [Shape](../../aspose.slides/shape/) 内容保存为 SVG 文件。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* 类 [IFormattedTextContainer](../iformattedtextcontainer/)
* 类 [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)