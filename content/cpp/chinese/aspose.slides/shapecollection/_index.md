---
title: ShapeCollection
second_title: Aspose.Slides for C++ API 参考
description: 表示一个形状集合。
type: docs
weight: 5110
url: /zh/aspose.slides/shapecollection/
---
## ShapeCollection 类

表示一个形状集合。

```cpp
class ShapeCollection : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::GroupShape>>,
                        public Aspose::Slides::IShapeCollection
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameCD](./addaudioframecd/)(**float**, **float**, **float**, **float**) override | 创建一个链接到 CD 曲目的新音频帧，并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameEmbedded](./addaudioframeembedded/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 创建一个包含嵌入式 WAV 文件的新音频帧，并将其添加到形状集合的末尾。嵌入的音频会添加到 [Presentation::get_Audios](../presentation/get_audios/) 集合中。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameEmbedded](./addaudioframeembedded/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 使用 [Presentation::get_Audios](../presentation/get_audios/) 列表中的现有音频对象，创建一个新音频帧并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameLinked](./addaudioframelinked/)(**float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 创建一个链接到外部音频文件的新音频帧，并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddAutoShape](./addautoshape/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | 创建一个具有默认格式的新自动形状，并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddAutoShape](./addautoshape/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 创建一个新自动形状并将其添加到形状集合的末尾，可选择使用默认模板格式进行初始化。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [AddChart](./addchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**) override | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [AddChart](./addchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **bool**) override | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**, **float**, **float**) override | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**) override | 创建指定形状的副本并将其添加到形状集合的末尾。新形状保留 *sourceShape* 的宽度和高度。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 创建指定形状的副本并将其添加到形状集合的末尾。克隆形状保留原始位置和大小。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [AddConnector](./addconnector/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | 创建一个具有默认模板样式的新连接器形状，并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [AddConnector](./addconnector/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 创建一个新连接器形状并将其添加到形状集合的末尾，可选择使用默认模板样式。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [AddGroupShape](./addgroupshape/)() override | 创建一个空的组形状并将其添加到形状集合的末尾。组的框架会自动调整以适应添加的任何形状。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [AddGroupShape](./addgroupshape/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgImage](../isvgimage/)\>, **float**, **float**, **float**, **float**) override | 创建一个新组形状，将指定的 SVG 图像转换为单独的形状，并将生成的组添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddMathShape](./addmathshape/)(**float**, **float**, **float**, **float**) override | 创建一个用于承载数学内容的新矩形自动形状，并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [AddOleObjectFrame](./addoleobjectframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [AddOleObjectFrame](./addoleobjectframe/)(**float**, **float**, **float**, **float**, [System::String](../../system/string/), [System::String](../../system/string/)) override | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrame](../ipictureframe/)\> [AddPictureFrame](./addpictureframe/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 创建一个包含指定图像的新图片框架，并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [AddSectionZoomFrame](./addsectionzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | 创建一个新的 [Section](../section/) 缩放框架并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [AddSectionZoomFrame](./addsectionzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 创建一个带预定义图像的新的 [Section](../section/) 缩放框架，并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[SmartArt::ISmartArt](../../aspose.slides.smartart/ismartart/)\> [AddSmartArt](./addsmartart/)(**float**, **float**, **float**, **float**, [SmartArt::SmartArtLayoutType](../../aspose.slides.smartart/smartartlayouttype/)) override | 创建一个 [SmartArt](../../aspose.slides.smartart/) 图表并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomFrame](../isummaryzoomframe/)\> [AddSummaryZoomFrame](./addsummaryzoomframe/)(**float**, **float**, **float**, **float**) override | 创建一个新的摘要缩放框架并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [AddTable](./addtable/)(**float**, **float**, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>) override | 创建一个新表格并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoFrame](../ivideoframe/)\> [AddVideoFrame](./addvideoframe/)(**float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 创建一个新视频帧并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoFrame](../ivideoframe/)\> [AddVideoFrame](./addvideoframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | 创建一个新视频帧并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [AddZoomFrame](./addzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 创建一个新缩放框架并将其添加到形状集合的末尾。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [AddZoomFrame](./addzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 创建一个新缩放框架并将其添加到形状集合的末尾。 |
| [iterator](./iterator/) [begin](./begin/)() | 获取指向集合中第一个元素（如果有）的迭代器。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 获取指向 const 限定实例中第一个元素（如果有）的迭代器。 |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | 获取指向 const 限定集合中第一个元素（如果有）的迭代器。 |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 获取指向 const 限定集合中最后一个元素之后的位置的迭代器（如果有）。 |
| void [Clear](./clear/)() override | 从形状集合中删除所有形状。 |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\>, **int32_t**) override | 将集合中的所有元素复制到指定的数组。 |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | 将集合中的所有元素复制到指定的数组。 |
| [iterator](./iterator/) [end](./end/)() | 获取指向集合中最后一个元素之后的位置的迭代器（如果有）。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | 获取指向 const 限定实例中最后一个元素之后的位置的迭代器（如果有）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **int32_t** [get_Count](./get_count/)() override | 获取集合实际包含的元素数量。只读 **int32_t**。 |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | 返回一个值，指示对集合的访问是否同步（线程安全）。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | 获取形状集合的父组形状对象。只读 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | 返回同步根。只读 [System::Object](../../system/object/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\>\> [GetEnumerator](./getenumerator/)() override | 返回一个枚举器，用于遍历集合。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等价实现。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [idx_get](./idx_get/)(**int32_t**) override | 获取指定索引处的元素。只读 [IShape](../ishape/)。 |
| **int32_t** [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 返回指定形状在集合中首次出现的零基索引。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameCD](./insertaudioframecd/)(**int32_t**, **float**, **float**, **float**, **float**) override | 创建一个链接到 CD 曲目的新音频帧，并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameEmbedded](./insertaudioframeembedded/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 创建一个包含嵌入式 WAV 文件的新音频帧，并将其插入到形状集合中指定的索引位置。嵌入的音频会添加到 [Presentation::get_Audios](../presentation/get_audios/) 集合中。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameEmbedded](./insertaudioframeembedded/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 使用 [Presentation::get_Audios](../presentation/get_audios/) 列表中的现有音频对象，创建一个新音频帧并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameLinked](./insertaudioframelinked/)(**int32_t**, **float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 创建一个链接到外部音频文件的新音频帧，并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [InsertAutoShape](./insertautoshape/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | 创建一个新自动形状并将其插入到形状集合中指定的索引位置，使用默认模板格式。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [InsertAutoShape](./insertautoshape/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 创建一个新自动形状并将其插入到形状集合中指定的索引位置，可选择使用默认模板样式进行初始化。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [InsertChart](./insertchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **int32_t**) override | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [InsertChart](./insertchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **int32_t**, **bool**) override | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**, **float**, **float**) override | 创建指定形状的副本并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**) override | 创建指定形状的副本并将其插入到形状集合中指定的索引位置。新形状保留 *sourceShape* 的宽度和高度。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 创建指定形状的副本并将其插入到形状集合中指定的索引位置。克隆形状保留原始位置和大小。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [InsertConnector](./insertconnector/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | 创建一个新连接器形状并将其插入到形状集合中指定的索引位置，使用默认模板样式。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [InsertConnector](./insertconnector/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 创建一个新连接器形状并将其插入到形状集合中指定的索引位置，可选择使用默认模板样式。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [InsertGroupShape](./insertgroupshape/)(**int32_t**) override | 创建一个空的组形状并将其插入到形状集合中指定的索引位置。组的框架会自动调整以适应添加的任何形状。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [InsertOleObjectFrame](./insertoleobjectframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | 创建一个新 OLE 对象框架并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [InsertOleObjectFrame](./insertoleobjectframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::String](../../system/string/), [System::String](../../system/string/)) override | 创建一个新 OLE 对象框架并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrame](../ipictureframe/)\> [InsertPictureFrame](./insertpictureframe/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 创建一个包含指定图像的新图片框架，并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [InsertSectionZoomFrame](./insertsectionzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | 创建一个新的 [Section](../section/) 缩放框架并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [InsertSectionZoomFrame](./insertsectionzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 创建一个带预定义图像的新的 [Section](../section/) 缩放框架，并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomFrame](../isummaryzoomframe/)\> [InsertSummaryZoomFrame](./insertsummaryzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**) override | 创建一个新的摘要缩放框架并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [InsertTable](./inserttable/)(**int32_t**, **float**, **float**, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>) override | 创建一个新表格并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoFrame](../ivideoframe/)\> [InsertVideoFrame](./insertvideoframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 创建一个新视频帧并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [InsertZoomFrame](./insertzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 创建一个新缩放框架并将其插入到形状集合中指定的索引位置。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [InsertZoomFrame](./insertzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 创建一个带预定义图像的新的缩放框架，并将其插入到形状集合中指定的索引位置。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 `is` 运算符。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 对序列应用累加函数。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判断序列的所有元素是否满足条件。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 判断序列是否包含任何元素。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判断序列中是否存在任意满足条件的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 将元素转换为指定类型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 连接两个序列。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 判断序列是否包含指定值。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 返回序列中元素的数量（通过直接计数计算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回满足指定条件的序列中元素的数量。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 返回序列的第一个元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回满足指定条件的序列的第一个元素。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 返回序列的第一个元素，如果序列为空则返回默认值。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 返回满足条件的序列的第一个元素，如果不存在则返回默认值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 对序列的元素进行分组。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 对序列的元素进行分组。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 返回序列的最后一个元素。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 返回序列的最后一个元素，如果序列为空则返回默认值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用变换函数，并返回最大结果值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用变换函数，并返回最小结果值。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 根据指定类型过滤序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 按 keySelector 选择的键值升序排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 按 keySelector 选择的键值降序排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 反转序列中元素的顺序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 转换序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 通过加入元素的索引，将序列的每个元素转换为新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 将序列的每个元素投影并将产生的序列合并为一个序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 从序列的开头返回指定数量的连续元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 从序列创建数组。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 从序列创建 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根据指定的谓词过滤序列。 |
| void [Lock](../../system/object/lock/)() | 实现 C# `lock()` 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的等价实现。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用 nullptr 按引用比较值类型对象。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串情形的特化。 |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 删除形状集合中首次出现的指定形状。 |
| void [RemoveAt](./removeat/)(**int32_t**) override | 删除形状集合中指定索引处的形状。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [Reorder](./reorder/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 将指定形状在形状集合中移动到新位置。 |
| void [Reorder](./reorder/)(**int32_t**, const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\>\&) override | 将指定的形状在形状集合中移动，从给定索引开始依次放置。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不要直接调用，请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少共享引用计数并返回其值。不要直接调用，请使用智能指针或 ThisProtector。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\> [ToArray](./toarray/)() override | 创建并返回包含所有形状的数组。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | 创建并返回包含指定范围内所有形状的数组。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的等价实现。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# `typeof([System.Object](../../system/object/))` 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# `lock()` 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 获取指向 const 限定实例中第一个元素（如果有）的迭代器。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 获取指向集合中第一个元素（如果有）的迭代器。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 获取指向 const 限定实例中最后一个元素之后的位置的迭代器（如果有）。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | 获取指向集合中最后一个元素之后的位置的迭代器（如果有）。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不要直接调用，请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不要直接调用，请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | 用作当前集合迭代器类型的集合类型。 |
| [iterator](./iterator/) | 迭代器类型。 |
| [const_iterator](./const_iterator/) | const 迭代器类型。 |
| [virtualized_iterator_element](./virtualized_iterator_element/) | 虚拟化元素类型。 |
| [virtualized_iterator](./virtualized_iterator/) | 虚拟化类型。 |

## 另见

* Class [DomObject](../domobject/)
* Class [IShapeCollection](../ishapecollection/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)