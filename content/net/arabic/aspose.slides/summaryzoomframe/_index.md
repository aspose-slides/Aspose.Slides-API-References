---
title: SummaryZoomFrame
second_title: مرجع API ل Aspose.Sildes لـ .NET
description: يمثل كائن Summary Zoom في شريحة.
type: docs
weight: 10790
url: /ar/aspose.slides/summaryzoomframe/
---
## فئة SummaryZoomFrame

يمثل كائن Summary Zoom في شريحة.

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | إرجاع أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | إرجاع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | إرجاع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | إرجاع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُرجع قيمة null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. ملاحظة: قد يُرجع قيمة null لبعض أنواع الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | إرجاع أو تعيين ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحديد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | إرجاع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المحدد لتمرير الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | إرجاع أو تعيين خيار 'وضع علامة كديكور'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحديد ما إذا كان الشكل مجموعًا. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحديد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | إرجاع تخطيط أقسام Summary Zoom في الإطار. القيمة الافتراضية هي GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: قد يُرجع قيمة null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | إرجاع أو تعيين اسم الشكل. يجب ألا يكون null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | إرجاع معرف فريد ذو نطاق شريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل بأمان من أي مكان في المستند. قراءة فقط UInt32. راجع أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | إرجاع كائن GroupShape الأب إذا كان الشكل مجموعًا. وإلا يُرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | إرجاع العنصر النائب للشكل. يُرجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | إرجاع عرض الشريحة الأب. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | إرجاع أو تعيين عدد الدرجات التي يدور بها الشكل حول محور Z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس اتجاه العقارب. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 خصائص) |
| [Slide](../../aspose.slides/shape/slide) { get; } | إرجاع الشريحة الأب للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | إرجاع [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) لكائن Summary Zoom Frame. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُرجع قيمة null لبعض الأنواع التي لا تحتوي على خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | إرجاع معرف داخلي ذو نطاق عرض يُقصد به الاستخدام من قبل الإضافات أو أكواد أخرى. لأن هذا القيمة قد تُعاد تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. راجع أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | إرجاع أو تعيين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | إرجاع أو تعيين إحداثي X للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | إرجاع أو تعيين إحداثي Y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | إرجاع موقع الشكل في ترتيب Z. Shapes[0] تُرجع الشكل في الخلف، وShapes[Shapes.Count - 1] تُرجع الشكل في المقدمة. قراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى قيمة محددة. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | إرجاع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يُورث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي مُورثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | إرجاع صورة مصغرة للشكل. يُستخدم نوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة افتراضيًا. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | إرجاع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | إرجاع الحدود البصرية للشكل محسوبة من محتواه المعروض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعريف أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | حفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | حفظ محتوى الشكل كملف SVG. |

### راجع أيضًا

* الفئة [GraphicalObject](../graphicalobject)
* الواجهة [ISummaryZoomFrame](../isummaryzoomframe)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->