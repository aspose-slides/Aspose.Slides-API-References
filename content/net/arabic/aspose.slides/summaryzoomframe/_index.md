---
title: SummaryZoomFrame
second_title: مرجع API لـ Aspose.Sildes for .NET
description: يمثل كائن Summary Zoom في شريحة.
type: docs
weight: 10770
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
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يرجع أو يضبط النص البديل المرتبط بشكل. قابل للقراءة والكتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يرجع أو يضبط عنوان النص البديل المرتبط بشكل. قابل للقراءة والكتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قابل للقراءة والكتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يرجع عدد نقاط الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يرجع البيانات المخصصة للشكل. للقراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص تأثير. للقراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص تعبئة. للقراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يرجع أو يضبط خصائص إطار الشكل. قابل للقراءة والكتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | يرجع أقفال الشكل. للقراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قابل للقراءة والكتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالماوس. قابل للقراءة والكتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يرجع مدير الارتباطات التشعبية. للقراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يرجع أو يضبط الارتباط التشعبي المحدد للتحريك فوق الفأرة. قابل للقراءة والكتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحصل أو يضبط خيار 'وضع علامة كزخرف'. قابل للقراءة والكتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | يحصل على تخطيط أقسام Summary Zoom داخل الإطار. القيمة الافتراضية هي GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص خط. للقراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يرجع أو يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قابل للقراءة والكتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يرجع معرفًا فريدًا محصورًا بالشرائح يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يرجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يُعيد null. للقراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يرجع العنصر النائب للشكل. يُعيد null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يرجع العرض التقديمي الأب للشرائح. للقراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يرجع أو يضبط خصائص إطار الشكل الخام. قابل للقراءة والكتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يرجع أو يضبط عدد الدرجات التي يتم تدوير الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. قابل للقراءة والكتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | يرجع أقفال الشكل. للقراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (خاصيتان) |
| [Slide](../../aspose.slides/shape/slide) { get; } | يرجع شريحة الأب للشكل. للقراءة فقط [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | يحصل على [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) لكائن Summary Zoom Frame. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يرجع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد لشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد. للقراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يرجع معرفًا داخليًا محصورًا بالعرض التقديمي يُقصد به الاستخدام من قبل الإضافات أو كود آخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحصل أو يضبط إحداثي x لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحصل أو يضبط إحداثي y لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط. قابل للقراءة والكتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يرجع موضع الشكل في الترتيب z. Shapes[0] تُعيد الشكل في الخلفية من الترتيب z، وShapes[Shapes.Count - 1] تُعيد الشكل في الأمام من الترتيب z. للقراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يرجع شكلًا أساسيًا للعنصر النائب (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي موروثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | يرجع صورة مصغرة للشكل. يتم استخدام النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على الحدود البصرية للشكل محسوبة من محتواه المعروض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GraphicalObject](../graphicalobject)
* واجهة [ISummaryZoomFrame](../isummaryzoomframe)
* نطاق الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->