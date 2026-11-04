---
title: ShapeCollection
second_title: مرجع API Aspose.Sildes لـ .NET
description: يمثل مجموعة من الأشكال.
type: docs
weight: 9880
url: /ar/aspose.slides/shapecollection/
---
## ShapeCollection فئة

Represents a collection of shapes.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. Int32 للقراءة فقط. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن من الخيوط). Boolean للقراءة فقط. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | يحصل على العنصر في الفهرس المحدد. [`IShape`](../ishape) للقراءة فقط. |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | يحصل على كائن الشكل الجماعي الأب لمجموعة الأشكال. [`IGroupShape`](../igroupshape) للقراءة فقط. |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | يعيد جذر التزامن. Object للقراءة فقط. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | ينشئ إطار صوتي جديد مرتبط بمسار CD ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | ينشئ إطار صوتي جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | ينشئ إطار صوتي جديد بملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | ينشئ إطار صوتي جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | ينشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، ويطبق تنسيق القالب الافتراضي اختياريًا. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | ينشئ مخططًا جديدًا، يهيئه ببيانات وسلاسل عينة، ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | ينشئ مخططًا جديدًا، يهيئه ببيانات وسلاسل عينة، ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. تحتفظ النسخة المستنسخة بموقع وحجم الأصل. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | ينشئ شكل موصل جديد بتنسيق القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، ويطبق تنسيق القالب الافتراضي اختياريًا. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | ينشئ شكل مجموعة فارغ جديد ويضيفه إلى نهاية مجموعة الأشكال. سيضبط إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | ينشئ شكل مجموعة جديد، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | ينشئ شكلًا تلقائيًا جديدًا على شكل مستطيل لاستضافة محتوى رياضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | ينشئ إطار تكبير قسم جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | ينشئ إطار تكبير قسم جديد بصورة مسبقة التعريف ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | ينشئ مخطط SmartArt جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | ينشئ إطار ملخص تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [Clear](../../aspose.slides/shapecollection/clear)() | يزيل جميع الأشكال من مجموعة الأشكال. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | يعيد كائنًا مُعدًا للتهيئة يتنقل عبر المجموعة. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | يعيد الفهرس الصفري لحدوث أول مرة للشكل المحدد في المجموعة. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | ينشئ إطار صوتي جديد مرتبط بمسار CD ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | ينشئ إطار صوتي جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | ينشئ إطار صوتي جديد بملف WAV مدمج ويدخله في مجموعة الأشكال عند الفهرس المحدد. يُضاف الصوت المدمج إلى مجموعة Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | ينشئ إطار صوتي جديد مرتبط بملف صوت خارجي ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد، ويطبق تنسيق القالب الافتراضي. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد، ويطبق تنسيق القالب الافتراضي اختياريًا. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | ينشئ مخططًا جديدًا، يهيئه ببيانات وسلاسل عينة، ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | ينشئ مخططًا جديدًا، يهيئه ببيانات وسلاسل عينة، ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | ينشئ نسخة من الشكل المحدد ويدخله في مجموعة الأشكال عند الفهرس المحدد. تحتفظ النسخة المستنسخة بموقع وحجم الأصل. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | ينشئ نسخة من الشكل المحدد ويدخله في مجموعة الأشكال عند الفهرس المحدد. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | ينشئ نسخة من الشكل المحدد ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | ينشئ شكل موصل جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد، ويطبق تنسيق القالب الافتراضي. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | ينشئ شكل موصل جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد، ويطبق تنسيق القالب الافتراضي اختياريًا. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | ينشئ شكل مجموعة فارغ جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد. سيضبط إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | ينشئ إطار كائن OLE جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | ينشئ إطار كائن OLE جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | ينشئ إطار تكبير قسم جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | ينشئ إطار تكبير قسم جديد بصورة مسبقة التعريف ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | ينشئ إطار ملخص تكبير جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | ينشئ جدولًا جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | ينشئ إطار فيديو جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | ينشئ إطار تكبير جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | ينشئ إطار تكبير جديد بصورة مسبقة التعريف ويدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | يزيل أول حدوث للشكل المحدد من مجموعة الأشكال. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | يزيل الشكل الموجود عند الفهرس المحدد من مجموعة الأشكال. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | ينقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | ينقل الأشكال المحددة داخل مجموعة الأشكال، ويضعها بدءًا من الفهرس المعطى. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد. |

### انظر أيضا

* فئة [DomObject&lt;TParent&gt;](../domobject-1)
* فئة [GroupShape](../groupshape)
* واجهة [IShapeCollection](../ishapecollection)
* مساحة الأسماء [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->