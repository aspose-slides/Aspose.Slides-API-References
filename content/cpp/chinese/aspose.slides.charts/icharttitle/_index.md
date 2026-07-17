---
title: IChartTitle
second_title: Aspose.Slides for C++ API 参考
description: 表示图表标题属性。
type: docs
weight: 911
url: /zh/aspose.slides.charts/icharttitle/
---
## IChartTitle 类

表示图表标题属性。

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | 使用参数 \"text\" 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 仿真 C# 式浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 仿真 C# 式浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | 指定图表元素的实际高度。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | 指定图表元素的实际宽度。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | 指定图表元素相对于图表左上角的实际 x 位置（左）。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | 指定图表元素相对于图表左上角的实际顶部位置。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | 获取图表元素顶部相对于图表高度的比例。只读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回图表。只读 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 返回标题的填充、线条、效果样式。只读 [IFormat](../iformat/)。 |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | 指定图表元素高度相对于图表高度的比例。读取 **float**。 |
| virtual **bool** [get_Overlay](./get_overlay/)() | 确定是否允许其他图表元素覆盖标题。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | 获取图表元素右侧相对于图表宽度的比例。只读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 返回图表文本格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | 可以包含富格式文本。如果此属性不为 null，则该格式化文本值会覆盖自动生成的文本。自动生成的文本是数据标签、值轴的显示单位标签、轴标题、图表标题、趋势线标签的隐式属性。自动生成的文本使用 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 属性进行格式化。只读 [ITextFrame](../../aspose.slides/itextframe/)。 |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | 指定图表元素宽度相对于图表宽度的比例。读取 **float**。 |
| virtual **float** [get_X](../ilayoutable/get_x/)() | 指定图表元素 x 位置（左）相对于图表宽度的比例。读取 **float**。 |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | 指定图表元素顶部相对于图表高度的比例。读取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等价实现。支持自定义对象的散列。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为目标类型描述的实例。相当于 C# 的 `is` 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的等价实现。支持自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并支持子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并支持子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，处理 string 与 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，处理字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | 指定图表元素高度相对于图表高度的比例。写入 **float**。 |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | 确定是否允许其他图表元素覆盖标题。写入 **bool**。 |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | 指定图表元素宽度相对于图表宽度的比例。写入 **float**。 |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | 指定图表元素 x 位置（左）相对于图表宽度的比例。写入 **float**。 |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | 指定图表元素顶部相对于图表高度的比例。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的等价实现。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [ILayoutable](../ilayoutable/)
* 类 [IOverridableText](../ioverridabletext/)
* 类 [IActualLayout](../iactuallayout/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)