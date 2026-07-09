---
title: IShapeCollection
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مجموعة من الأشكال.
type: docs
weight: 6980
url: /ar/aspose.slides/ishapecollection/
---
## IShapeCollection الواجهة

يمثل مجموعة من الأشكال.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | يحصل على العنصر في الفهرس المحدد. للقراءة فقط [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | يحصل على كائن مجموعة الأشكال الأصلية لمجموعة الأشكال. للقراءة فقط [`IGroupShape`](../igroupshape). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | ينشئ إطار صوت جديد مرتبط بمسار قرص مدمج ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | ينشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | ينشئ إطار صوت جديد بملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | ينشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، مع إمكانية تطبيق تنسيق القالب الافتراضي، ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. تحتفظ النسخة المستنسخة بموقع وحجم الأصل. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | ينشئ شكل موصل جديد بنمط القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق نمط القالب الافتراضي. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. سيتكيف إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | ينشئ مجموعة أشكال جديدة، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | ينشئ شكلًا تلقائيًا على شكل مستطيل لاستضافة محتوى رياضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | ينشئ إطار تكبير قسم جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | ينشئ إطار تكبير قسم جديد بصورة معرفة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | ينشئ إطار تكبير ملخص جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | ينشئ إطار تكبير جديد بصورة معرفة مسبقًا ويضيفه إلى النهاية مجموعة الأشكال. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | يزيل جميع الأشكال من مجموعة الأشكال. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | يعيد الفهرس الصفري للظهور الأول للشكل المحدد في المجموعة. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | ينشئ إطار صوت جديد مرتبط بمسار قرص مدمج ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | ينشئ إطار صوت جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | ينشئ إطار صوت جديد بملف WAV مدمج ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تطبيق نمط القالب الافتراضي. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، مع إمكانية تطبيق نمط القالب الافتراضي، ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | ينشئ نسخة من الشكل المحدد ويُدرجها في مجموعة الأشكال عند الفهرس المحدد. تحتفظ النسخة المستنسخة بموقع وحجم الأصل. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | ينشئ نسخة من الشكل المحدد ويُدرجها في مجموعة الأشكال عند الفهرس المحدد. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | ينشئ نسخة من الشكل المحدد ويُدرجها في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق نمط القالب الافتراضي. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تطبيق نمط القالب الافتراضي. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | ينشئ مجموعة أشكال فارغة جديدة ويُدرجها في مجموعة الأشكال عند الفهرس المحدد. سيتكيف إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | ينشئ إطار تكبير قسم جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | ينشئ إطار تكبير قسم جديد بصورة معرفة مسبقًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | ينشئ إطار تكبير ملخص جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | ينشئ إطار فيديو جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | ينشئ إطار تكبير جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | ينشئ إطار تكبير جديد بصورة معرفة مسبقًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | يزيل الظهور الأول للشكل المحدد من مجموعة الأشكال. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | يزيل الشكل عند الفهرس المحدد من مجموعة الأشكال. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | ينقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | ينقل الأشكال المحددة داخل مجموعة الأشكال، ويضعها بدءًا من الفهرس المحدد. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد. |

### انظر أيضًا

* الواجهة [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* الواجهة [IShape](../ishape)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->