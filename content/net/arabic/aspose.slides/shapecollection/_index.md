---
title: ShapeCollection
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مجموعة من الأشكال.
type: docs
weight: 9860
url: /ar/aspose.slides/shapecollection/
---
## فئة ShapeCollection

يمثل مجموعة من الأشكال.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قراءة فقط Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). قراءة فقط Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | يحصل على العنصر في الفهرس المحدد. قراءة فقط [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | يحصل على كائن الشكل المجمع الأصل لمجموعة الأشكال. قراءة فقط [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | إرجاع جذر المزامنة. قراءة فقط Object. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | إنشاء إطار صوتي جديد مرتبط بمسار CD وإضافته إلى نهاية مجموعة الأشكال. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | إنشاء إطار صوتي جديد وإضافته إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | إنشاء إطار صوتي جديد بملف WAV مضمّن وإضافته إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المضمّن إلى مجموعة Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | إنشاء إطار صوتي جديد مرتبط بملف صوت خارجي وإضافته إلى نهاية مجموعة الأشكال. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | إنشاء شكل تلقائي جديد بتنسيق افتراضي وإضافته إلى نهاية مجموعة الأشكال. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | إنشاء شكل تلقائي جديد وإضافته إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | إنشاء مخطط جديد، وتهيئته ببيانات سلسلة تجريبية وإعدادات، وإضافته إلى نهاية مجموعة الأشكال. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | إنشاء مخطط جديد، وتهيئته ببيانات سلسلة تجريبية وإعدادات، وإضافته إلى نهاية مجموعة الأشكال. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | إنشاء نسخة من الشكل المحدد وإضافتها إلى نهاية مجموعة الأشكال. يحتفظ الشكل المستنسخ بموقعه وحجمه الأصلي. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | إنشاء نسخة من الشكل المحدد وإضافتها إلى نهاية مجموعة الأشكال. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | إنشاء نسخة من الشكل المحدد وإضافتها إلى نهاية مجموعة الأشكال. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | إنشاء شكل موصل جديد بنمط قالب افتراضي وإضافته إلى نهاية مجموعة الأشكال. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | إنشاء شكل موصل جديد وإضافته إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق نمط القالب الافتراضي. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | إنشاء شكل مجموعة فارغ جديد وإضافته إلى نهاية مجموعة الأشكال. سيتكيف إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | إنشاء شكل مجموعة جديد، تحويل صورة SVG المحددة إلى أشكال فردية، وإضافة المجموعة الناتجة إلى نهاية مجموعة الأشكال. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | إنشاء شكل مستطيل تلقائي جديد لاستضافة محتوى رياضي وإضافته إلى نهاية مجموعة الأشكال. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | إنشاء إطار كائن OLE جديد وإضافته إلى نهاية مجموعة الأشكال. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | إنشاء إطار كائن OLE جديد وإضافته إلى نهاية مجموعة الأشكال. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | إنشاء إطار صورة جديد يحتوي على الصورة المحددة وإضافته إلى نهاية مجموعة الأشكال. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | إنشاء إطار تكبير قسم جديد وإضافته إلى نهاية مجموعة الأشكال. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | إنشاء إطار تكبير قسم جديد بصورة محددة مسبقًا وإضافته إلى نهاية مجموعة الأشكال. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | إنشاء مخطط SmartArt وإضافته إلى نهاية مجموعة الأشكال. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | إنشاء إطار تكبير ملخص جديد وإضافته إلى نهاية مجموعة الأشكال. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | إنشاء جدول جديد وإضافته إلى نهاية مجموعة الأشكال. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | إنشاء إطار فيديو جديد وإضافته إلى نهاية مجموعة الأشكال. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | إنشاء إطار فيديو جديد وإضافته إلى نهاية مجموعة الأشكال. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | إنشاء إطار تكبير جديد وإضافته إلى نهاية مجموعة الأشكال. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | إنشاء إطار تكبير جديد وإضافته إلى نهاية مجموعة الأشكال. |
| [Clear](../../aspose.slides/shapecollection/clear)() | إزالة جميع الأشكال من مجموعة الأشكال. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | إرجاع كائن Enumerator يمر عبر المجموعة. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | إرجاع الفهرس الصفري للحدوث الأول للشكل المحدد في المجموعة. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | إنشاء إطار صوتي جديد مرتبط بمسار CD وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | إنشاء إطار صوتي جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | إنشاء إطار صوتي جديد بملف WAV مضمّن وإدراجه في مجموعة الأشكال عند الفهرس المحدد. يتم إضافة الصوت المضمّن إلى مجموعة Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | إنشاء إطار صوتي جديد مرتبط بملف صوت خارجي وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | إنشاء شكل تلقائي جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | إنشاء شكل تلقائي جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تهيئته بنمط القالب الافتراضي. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | إنشاء مخطط جديد، وتهيئته ببيانات سلسلة تجريبية وإعدادات، وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | إنشاء مخطط جديد، وتهيئته ببيانات سلسلة تجريبية وإعدادات، وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | إنشاء نسخة من الشكل المحدد وإدراجها في مجموعة الأشكال عند الفهرس المحدد. يحتفظ الشكل المستنسخ بموقعه وحجمه الأصلي. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | إنشاء نسخة من الشكل المحدد وإدراجها في مجموعة الأشكال عند الفهرس المحدد. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | إنشاء نسخة من الشكل المحدد وإدراجها في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | إنشاء شكل موصل جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق نمط القالب الافتراضي. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | إنشاء شكل موصل جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تطبيق نمط القالب الافتراضي. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | إنشاء شكل مجموعة فارغ جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد. سيتكيف إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | إنشاء إطار كائن OLE جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | إنشاء إطار كائن OLE جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | إنشاء إطار صورة جديد يحتوي على الصورة المحددة وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | إنشاء إطار تكبير قسم جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | إنشاء إطار تكبير قسم جديد بصورة محددة مسبقًا وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | إنشاء إطار تكبير ملخص جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | إنشاء جدول جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | إنشاء إطار فيديو جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | إنشاء إطار تكبير جديد وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | إنشاء إطار تكبير جديد بصورة محددة مسبقًا وإدراجه في مجموعة الأشكال عند الفهرس المحدد. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | إزالة أول حدوث للشكل المحدد من مجموعة الأشكال. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | إزالة الشكل عند الفهرس المحدد من مجموعة الأشكال. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | نقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | نقل الأشكال المحددة داخل مجموعة الأشكال، وضعها بدءًا من الفهرس المحدد. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | إنشاء وإرجاع مصفوفة تحتوي على جميع الأشكال. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | إنشاء وإرجاع مصفوفة تحتوي على جميع الأشكال في النطاق المحدد. |

### انظر أيضًا

* فئة [DomObject&lt;TParent&gt;](../domobject-1)
* فئة [GroupShape](../groupshape)
* واجهة [IShapeCollection](../ishapecollection)
* نطاق [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->