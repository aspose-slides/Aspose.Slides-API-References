---
title: IPictureFillFormat
second_title: Aspose.Slides for C++ API 参考
description: 表示一种图片填充样式。
type: docs
weight: 3225
url: /zh/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat 类

表示一种图片填充样式。

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | 通过根据形状大小和指定的分辨率缩小图像大小来压缩图像。可选地，它还会删除裁剪区域。 |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | 通过根据形状大小和指定的分辨率缩小图像大小来压缩图像。可选地，它还会删除裁剪区域。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | 删除填充[Picture](../picture/)的裁剪区域。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点数比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点数比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | 返回从图片底部裁剪掉的真实图像高度的百分比数。读取 **float**。 |
| virtual **float** [get_CropLeft](./get_cropleft/)() | 返回从图片左侧裁剪掉的真实图像宽度的百分比数。读取 **float**。 |
| virtual **float** [get_CropRight](./get_cropright/)() | 返回从图片右侧裁剪掉的真实图像宽度的百分比数。读取 **float**。 |
| virtual **float** [get_CropTop](./get_croptop/)() | 返回从图片顶部裁剪掉的真实图像高度的百分比数。读取 **float**。 |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | 返回用于填充图片的 DPI。读取 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | 返回图片。只读 [ISlidesPicture](../islidespicture/)。 |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | 返回图片填充模式。读取 [Slides::PictureFillMode](../picturefillmode/)。 |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | 返回填充矩形的底部边缘，该边缘由相对于形状边界框底部边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外延。读取 **float**。 |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | 返回填充矩形的左侧边缘，由相对于形状边界框左侧边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外延。读取 **float**。 |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | 返回填充矩形的右侧边缘，由相对于形状边界框右侧边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外延。读取 **float**。 |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | 返回填充矩形的顶部边缘，由相对于形状边界框顶部边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外延。读取 **float**。 |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | 返回纹理在形状内部的对齐方式。此设置控制纹理图案的起始点以及它在形状上的重复方式。读取 [RectangleAlignment](../rectanglealignment/)。 |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | 沿水平、垂直或两个轴翻转纹理平铺。读取 [Slides::TileFlip](../tileflip/)。 |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | 返回纹理相对于形状原点的水平偏移（单位：点）。正值使纹理向右移动，负值使纹理向左移动。读取 **float**。 |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | 返回纹理相对于形状原点的垂直偏移（单位：点）。正值使纹理向下移动，负值使纹理向上移动。读取 **float**。 |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | 返回纹理填充的水平比例，以百分比表示。读取 **float**。 |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | 返回纹理填充的垂直比例，以百分比表示。读取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的模拟。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的模拟。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | 设置从图片底部裁剪掉的真实图像高度的百分比数。写入 **float**。 |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | 设置从图片左侧裁剪掉的真实图像宽度的百分比数。写入 **float**。 |
| virtual void [set_CropRight](./set_cropright/)(**float**) | 设置从图片右侧裁剪掉的真实图像宽度的百分比数。写入 **float**。 |
| virtual void [set_CropTop](./set_croptop/)(**float**) | 设置从图片顶部裁剪掉的真实图像高度的百分比数。写入 **float**。 |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | 设置用于填充图片的 DPI。写入 **int32_t**。 |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | 设置图片填充模式。写入 [Slides::PictureFillMode](../picturefillmode/)。 |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | 设置填充矩形的底部边缘，...写入 **float**。 |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | 设置填充矩形的左侧边缘，...写入 **float**。 |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | 设置填充矩形的右侧边缘，...写入 **float**。 |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | 设置填充矩形的顶部边缘，...写入 **float**。 |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | 设置纹理在形状内部的对齐方式。此设置控制纹理图案的起始点以及它在形状上的重复方式。写入 [RectangleAlignment](../rectanglealignment/)。 |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | 沿水平、垂直或两个轴翻转纹理平铺。写入 [Slides::TileFlip](../tileflip/)。 |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | 设置纹理相对于形状原点的水平偏移（单位：点）。正值使纹理向右移动，负值使纹理向左移动。写入 **float**。 |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | 设置纹理相对于形状原点的垂直偏移（单位：点）。正值使纹理向下移动，负值使纹理向上移动。写入 **float**。 |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | 设置纹理填充的水平比例，以百分比表示。写入 **float**。 |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | 设置纹理填充的垂直比例，以百分比表示。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而不是共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的模拟。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [IFillParamSource](../ifillparamsource/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)