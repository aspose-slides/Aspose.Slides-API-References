---
title: IParagraphFormat
second_title: Aspose.Slides C++ API 参考
description: 此类包含段落格式属性。与 IParagraphFormatEffectiveData 不同，此类的所有属性均为可写。
type: docs
weight: 3147
url: /zh/aspose.slides/iparagraphformat/
---
## IParagraphFormat 类


此类包含段落格式属性。与 [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) 不同，此类的所有属性都是可写的。

```cpp
class IParagraphFormat : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | 返回段落中不带继承的文本对齐方式。阅读 [TextAlignment](../textalignment/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | 返回段落的项目符号格式。只读 [IBulletFormat](../ibulletformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | 返回段落的默认部分格式。未应用继承。只读 [IPortionFormat](../iportionformat/)。 |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | 返回不带继承的默认制表位大小。读取 **float**。 |
| virtual **int16_t** [get_Depth](./get_depth/)() | 返回段落的深度。值 0 表示未定义。读取 **int16_t**。 |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | 确定段落中是否使用东亚换行。未应用继承。阅读 [NullableBool](../nullablebool/)。 |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | 返回段落中不带继承的字体对齐方式。阅读 [Slides::FontAlignment](../fontalignment/)。 |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | 确定段落中是否使用悬挂标点。未应用继承。阅读 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_Indent](./get_indent/)() | 返回段落首行缩进/悬挂缩进（无继承）。悬挂缩进可使用负值定义。读取 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | 确定段落中是否使用拉丁换行。未应用继承。阅读 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | 返回段落左边距（无继承）。读取 **float**。 |
| virtual **float** [get_MarginRight](./get_marginright/)() | 返回段落右边距（无继承）。读取 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | 确定段落中是否使用从右到左书写。未应用继承。阅读 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | 设置段落最后一行之后的空间（无继承）。正值表示空白空间应为字体大小的百分比。负值表示空白空间的点大小。读取 **float**。 |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | 设置段落第一行之前的空间（无继承）。正值表示空白空间应为字体大小的百分比。负值表示空白空间的点大小。读取 **float**。 |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | 设置段落基线之间的空间。正值表示百分比，负值表示点数大小。未应用继承。读取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | 返回指定索引处的段落制表位。未应用继承。只读 [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | 返回段落的制表位集合。未应用继承。只读 [ITabCollection](../itabcollection/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | 获取应用继承后的有效段落格式数据。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | 设置段落中不带继承的文本对齐方式。写入 [TextAlignment](../textalignment/)。 |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | 设置不带继承的默认制表位大小。写入 **float**。 |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | 设置段落的深度。值 0 表示未定义。写入 **int16_t**。 |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | 确定段落中是否使用东亚换行。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | 设置段落中不带继承的字体对齐方式。写入 [Slides::FontAlignment](../fontalignment/)。 |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | 确定段落中是否使用悬挂标点。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_Indent](./set_indent/)(**float**) | 设置段落首行缩进/悬挂缩进（无继承）。悬挂缩进可使用负值定义。写入 **float**。 |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | 确定段落中是否使用拉丁换行。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | 设置段落左边距（无继承）。写入 **float**。 |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | 设置段落右边距（无继承）。写入 **float**。 |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | 确定段落中是否使用从右到左书写。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | 设置段落最后一行之后的空间（无继承）。正值表示空白空间应为字体大小的百分比。负值表示空白空间的点大小。写入 **float**。 |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | 设置段落第一行之前的空间（无继承）。正值表示空白空间应为字体大小的百分比。负值表示空白空间的点大小。写入 **float**。 |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | 设置段落基线之间的空间。正值表示百分比，负值表示点数大小。未应用继承。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注


此类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，需要使用 [IParagraphFormat::GetEffective](./geteffective/) 方法，该方法返回一个 [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) 实例。

## 参见

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)