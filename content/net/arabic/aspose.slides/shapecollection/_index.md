---
title: ShapeCollection
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مجموعة من الأشكال.
type: docs
weight: 9860
url: /ar/aspose.slides/shapecollection/
---
## ShapeCollection فئة

يمثل مجموعة من الأشكال.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## الخصائص

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. للقراءة فقط Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للأنشطة المتعددة). للقراءة فقط Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | يحصل على العنصر في الفهرس المحدد. للقراءة فقط [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | يحصل على كائن شكل المجموعة الأصلية لمجموعة الأشكال. للقراءة فقط [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | يعيد جذر المزامنة. للقراءة فقط Object. |

## الطرق

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | ينشئ إطار صوتي جديد مرتبط بمسار CD ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | ينشئ إطار صوتي جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | ينشئ إطار صوتي جديد بملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | ينشئ إطار صوتي جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | ينشئ شكلًا تلقائيًا جديدًا بالتنسيق الافتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | ينشئ مخططًا جديدًا، يهيئه ببيانات وعينات سلسلة وإعدادات مثال، ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | ينشئ مخططًا جديدًا، يهيئه ببيانات وعينات سلسلة وإعدادات مثال، مع إمكانية تطبيق تنسيق القالب الافتراضي، ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. يحتفظ الشكل المستنسخ بموضعه وحجمه الأصلي. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | ينشئ شكل موصل جديد بنمط القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق نمط القالب الافتراضي. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. سيتضبط إطار المجموعة تلقائيًا لاستيعاب أي أشكال تُضاف إليها. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | ينشئ مجموعة أشكال جديدة، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | ينشئ شكلًا مستطيلًا تلقائيًا جديدًا لاستضافة المحتوى الرياضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | ينشئ إطار تكبير قسم جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | ينشئ إطار تكبير قسم جديد بصورة مسبقة التعريف ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | ينشئ إطار تكبير ملخص جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [Clear](../../aspose.slides/shapecollection/clear)() | يزيل جميع الأشكال من مجموعة الأشكال. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | يعيد عدادًا يتنقل عبر المجموعة. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | يعيد الفهرس القائم على الصفر لأول ظهور للشكل المحدد في المجموعة. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | ينشئ إطار صوتي جديد مرتبط بمسار CD ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | ينشئ إطار صوتي جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | ينشئ إطار صوتي جديد بملف WAV مدمج ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | ينشئ إطار صوتي جديد مرتبط بملف صوت خارجي ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مطبقًا تنسيق القالب الافتراضي. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تهيئته بنمط القالب الافتراضي. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | ينشئ مخططًا جديدًا، يهيئه ببيانات وعينات سلسلة وإعدادات مثال، ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | ينشئ مخططًا جديدًا، يهيئه ببيانات وعينات سلسلة وإعدادات مثال، مع إمكانية تطبيق تنسيق القالب الافتراضي، ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | ينشئ نسخة من الشكل المحدد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. يحتفظ الشكل المستنسخ بموضعه وحجمه الأصلي. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | ينشئ نسخة من الشكل المحدد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | ينشئ نسخة من الشكل المحدد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مطبقًا نمط القالب الافتراضي. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تطبيق نمط القالب الافتراضي. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | ينشئ مجموعة أشكال فارغة جديدة ويُدرجها في مجموعة الأشكال عند الفهرس المحدد. سيتضبط إطار المجموعة تلقائيًا لاستيعاب أي أشكال تُضاف إليها. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | ينشئ إطار تكبير قسم جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | ينشئ إطار تكبير قسم جديد بصورة مسبقة التعريف ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | ينشئ إطار تكبير ملخص جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | ينشئ إطار فيديو جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | ينشئ إطار تكبير جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | ينشئ إطار تكبير جديد بصورة مسبقة التعريف ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | يزيل أول ظهور للشكل المحدد من مجموعة الأشكال. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | يزيل الشكل الموجود عند الفهرس المحدد من مجموعة الأشكال. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | ينقل الشكل المحدد إلى موقع جديد داخل مجموعة الأشكال. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | ينقل الأشكال المحددة داخل مجموعة الأشكال، موضعها يبدأ من الفهرس المحدد. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد. |

### انظر أيضًا

* فئة [DomObject&lt;TParent&gt;](../domobject-1)
* فئة [GroupShape](../groupshape)
* واجهة [IShapeCollection](../ishapecollection)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->