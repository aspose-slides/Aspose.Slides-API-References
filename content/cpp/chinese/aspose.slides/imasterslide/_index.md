---
title: IMasterSlide
second_title: Aspose.Slides for C++ API 参考
description: 表示演示文稿中的母版幻灯片。
type: docs
weight: 2926
url: /zh/aspose.slides/imasterslide/
---
## IMasterSlide 类

表示演示文稿中的母版幻灯片。

```cpp
class IMasterSlide : public virtual Aspose::Slides::IBaseSlide,
                     public Aspose::Slides::Theme::IMasterThemeable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](./)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) | 创建一个基于当前母版的新母版幻灯片，将外部主题应用于其上，并将创建的母版幻灯片应用于所有依赖的幻灯片。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | 返回此可设置主题对象的有效主题。 |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | 确定两个 [IBaseSlide](../ibaseslide/) 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画和其他设置等均相等，则两张幻灯片相等。比较不考虑唯一标识符值，例如 SlideId，以及动态内容，例如 Date [Placeholder](../placeholder/) 中的当前日期值。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | 查找具有指定替代文本的形状的首次出现。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | 返回幻灯片的背景。只读 [IBackground](../ibackground/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() | 返回正文文本的样式。只读 [ITextStyle](../itextstyle/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | 返回指定索引处的 ActiveX 控件。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | 返回幻灯片上 ActiveX 控件的集合。只读 [IControlCollection](../icontrolcollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | 返回幻灯片的自定义数据。只读 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | 返回母版幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../idrawingguidescollection/)。 |
| virtual **bool** [get_HasDependingSlides](./get_hasdependingslides/)() | 如果至少存在一张依赖此母版幻灯片的幻灯片，则返回 true。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | 返回母版幻灯片的 HeaderFooter 管理器。只读 [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | 提供对包含的超链接的便捷访问。只读 [IHyperlinkQueries](../ihyperlinkqueries/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | 返回此母版幻灯片在指定索引处的子布局幻灯片。只读 [Aspose::Slides::ILayoutSlide](../ilayoutslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | 返回此母版幻灯片的子布局幻灯片集合。只读 [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | 返回幻灯片的名称。读取 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() | 返回其他文本的样式。只读 [ITextStyle](../itextstyle/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../ipresentation/)。 |
| virtual **bool** [get_Preserve](./get_preserve/)() | 确定当所有跟随该母版的幻灯片被删除时，是否删除相应的母版。注意：[Aspose.Slides](../) 永远不会自行移除未使用的母版，如需实际移除未使用的母版，请调用 [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/)。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | 返回指定索引处的形状。只读 [Aspose::Slides::IShape](../ishape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | 返回幻灯片的形状集合。只读 [IShapeCollection](../ishapecollection/)。 |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | 指定是否在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 **false**。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../ibaseslide/)。 |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | 返回幻灯片的 ID。只读 **uint32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | 返回 TransitionEx 对象，其中包含指定幻灯片在放映期间如何切换的信息。只读 [ISlideShowTransition](../islideshowtransition/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | 返回母版主题管理器。只读 [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | 返回动画时间轴对象。只读 [IAnimationTimeLine](../ianimationtimeline/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() | 返回标题文本的样式。只读 [ITextStyle](../itextstyle/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() | 返回一个包含所有依赖此母版幻灯片的幻灯片的数组。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# 的 [Object.GetHashCode()](../../system/object/gethashcode/) 方法。用于自定义对象的散列。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | 在所有可接受的形状的所有段落中合并具有相同格式的文本运行。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# 的 [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。用于克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际并未复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际并未复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对 string 与 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数降低指定的值。 |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | 设置幻灯片的名称。写入 [System::String](../../system/string/)。 |
| virtual void [set_Preserve](./set_preserve/)(**bool**) | 确定当所有跟随该母版的幻灯片被删除时，是否删除相应的母版。注意：[Aspose.Slides](../) 永远不会自行移除未使用的母版，如需实际移除未使用的母版，请调用 [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/)。写入 **bool**。 |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | 指定是否在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 **false**。写入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# 的 [Object.ToString()](../../system/object/tostring/) 方法。用于将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [IBaseSlide](../ibaseslide/)
* 类 [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)