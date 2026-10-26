---
title: PictureFillFormat
second_title: Aspose.Slides C++ API 参考
description: 表示一种图片填充样式。
type: docs
weight: 4720
url: /zh/aspose.slides/picturefillformat/
---
## PictureFillFormat 类

表示一种图片填充样式。

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | 根据形状大小和指定分辨率压缩图像。可选地，还会删除裁剪区域。 |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | 根据形状大小和指定分辨率压缩图像。可选地，还会删除裁剪区域。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | 删除填充 [Picture](../picture/) 的裁剪区域。 |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 与指定对象比较。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使两个 NaN 被视为相等，尽管 IEC 60559:1989 规定 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使两个 NaN 被视为相等，尽管 IEC 60559:1989 规定 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **float** [get_CropBottom](./get_cropbottom/)() override | 返回实际图像高度被裁剪掉的底部的百分比。只读 **float**。 |
| **float** [get_CropLeft](./get_cropleft/)() override | 返回实际图像宽度被裁剪掉的左侧的百分比。只读 **float**。 |
| **float** [get_CropRight](./get_cropright/)() override | 返回实际图像宽度被裁剪掉的右侧的百分比。只读 **float**。 |
| **float** [get_CropTop](./get_croptop/)() override | 返回实际图像高度被裁剪掉的顶部的百分比。只读 **float**。 |
| **int32_t** [get_Dpi](./get_dpi/)() override | 返回用于填充图片的 DPI。只读 **int32_t**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../ipresentationcomponent/)。只读 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | 返回图片。只读 [ISlidesPicture](../islidespicture/)。 |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | 返回图片填充模式。读取 [Slides::PictureFillMode](../picturefillmode/)。 |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | 返回填充矩形的底部边缘，该边缘由相对于形状边界框底部的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。只读 **float**。 |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | 返回填充矩形的左侧边缘，该边缘由相对于形状边界框左侧的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。只读 **float**。 |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | 返回填充矩形的右侧边缘，该边缘由相对于形状边界框右侧的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。只读 **float**。 |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | 返回填充矩形的顶部边缘，该边缘由相对于形状边界框顶部的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。只读 **float**。 |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | 返回纹理在形状内的对齐方式。此设置控制纹理模式的起始点以及在形状上的重复方式。读取 [RectangleAlignment](../rectanglealignment/)。 |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | 围绕其水平、垂直或两个轴翻转纹理平铺。读取 [Slides::TileFlip](../tileflip/)。 |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | 返回纹理相对于形状原点的水平偏移（点）。正值向右移动纹理，负值向左移动。只读 **float**。 |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | 返回纹理相对于形状原点的垂直偏移（点）。正值向下移动纹理，负值向上移动。只读 **float**。 |
| **float** [get_TileScaleX](./get_tilescalex/)() override | 以百分比返回纹理填充的水平比例。只读 **float**。 |
| **float** [get_TileScaleY](./get_tilescaley/)() override | 以百分比返回纹理填充的垂直比例。只读 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | 设置实际图像高度被裁剪掉的底部的百分比。写入 **float**。 |
| void [set_CropLeft](./set_cropleft/)(**float**) override | 设置实际图像宽度被裁剪掉的左侧的百分比。写入 **float**。 |
| void [set_CropRight](./set_cropright/)(**float**) override | 设置实际图像宽度被裁剪掉的右侧的百分比。写入 **float**。 |
| void [set_CropTop](./set_croptop/)(**float**) override | 设置实际图像高度被裁剪掉的顶部的百分比。写入 **float**。 |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | 设置用于填充图片的 DPI。写入 **int32_t**。 |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | 设置图片填充模式。写入 [Slides::PictureFillMode](../picturefillmode/)。 |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | 设置填充矩形的底部边缘，该边缘由相对于形状边界框底部的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。写入 **float**。 |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | 设置填充矩形的左侧边缘，该边缘由相对于形状边界框左侧的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。写入 **float**。 |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | 设置填充矩形的右侧边缘，该边缘由相对于形状边界框右侧的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。写入 **float**。 |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | 设置填充矩形的顶部边缘，该边缘由相对于形状边界框顶部的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。写入 **float**。 |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | 设置纹理在形状内的对齐方式。此设置控制纹理模式的起始点以及在形状上的重复方式。写入 [RectangleAlignment](../rectanglealignment/)。 |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | 围绕其水平、垂直或两个轴翻转纹理平铺。写入 [Slides::TileFlip](../tileflip/)。 |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | 设置纹理相对于形状原点的水平偏移（点）。正值向右移动纹理，负值向左移动。写入 **float**。 |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | 设置纹理相对于形状原点的垂直偏移（点）。正值向下移动纹理，负值向上移动。写入 **float**。 |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | 设置纹理填充的水平比例（百分比）。写入 **float**。 |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | 设置纹理填充的垂直比例（百分比）。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 另见

* 类 [PVIObject](../pviobject/)
* 类 [IPictureFillFormat](../ipicturefillformat/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)