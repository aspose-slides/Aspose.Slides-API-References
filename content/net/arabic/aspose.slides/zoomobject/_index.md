---
title: ZoomObject
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل كائن Zoom في شريحة.
type: docs
weight: 11870
url: /ar/aspose.slides/zoomobject/
---
## ZoomObject فئة

يمثل كائن Zoom في شريحة.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يعيد أو يضبط النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الخاصية تحدد كيف سيُعرض الشكل في وضع العرض بالأبيض والأسود.. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يعيد عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يعيد البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يعيد أو يضبط خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | يعيد أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحصل أو يضبط ارتفاع الشكل، بالوحدات النقطية. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفياً. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يعيد أو يضبط الارتباط الفائق المحدد للنقر الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يعيد مدير الارتباط الفائق. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يعيد أو يضبط الارتباط الفائق المحدد لتجاوز الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | يحصل أو يضبط نوع الصورة لكائن Zoom. قراءة/كتابة [`ZoomImageType`](../zoomimagetype). القيمة الافتراضية: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحصل أو يضبط خيار 'وضع كديكور'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجمعاً. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يعيد أو يضبط اسم الشكل. يجب ألا يكون فارغاً. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يعيد معرفًا فريدًا محصورًا بالعرض الشرائحي يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو رمز التفاعل بالإشارة إلى الشكل بشكل موثوق من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يعيد كائن GroupShape الأب إذا كان الشكل مجمعًا. وإلا يعيد null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يعيد العنصر النائب للشكل. يعيد null إذا لم يكن لل shape عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يعيد العرض التقديمي الأصلي للشريحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يعيد أو يضبط خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | يحصل أو يضبط سلوك التنقل في عرض الشرائح. قراءة/كتابة Boolean. القيمة الافتراضية: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يعيد أو يضبط عدد درجات دوران الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس اتجاهها. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | يعيد أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (خاصيتان) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | يحصل أو يضبط قيمة تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. قراءة/كتابة Boolean. القيمة الافتراضية: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | يعيد الشريحة الأم للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يعيد null لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | يحصل على مدة الانتقال بين Zoom والشريحة. قراءة/كتابة Single. القيمة الافتراضية: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يعيد معرفًا داخليًا محصورًا بالعرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو أي رمز آخر. بما أن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحصل أو يضبط عرض الشكل، بالوحدات النقطية. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحصل أو يضبط إحداثي x للزاوية العلوية اليسرى للشكل، بالوحدات النقطية. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحصل أو يضبط إحداثي y للزاوية العلوية اليسرى للشكل، بالوحدات النقطية. قراءة/كتابة Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | يحصل أو يضبط صورة لكائن Zoom. قراءة/كتابة [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يعيد موضع الشكل في ترتيب z. Shapes[0] يعيد الشكل في خلفية الترتيب، و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة الترتيب. قراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسة الذي يُورّث منه الشكل الحالي). يُعاد null إذا لم يكن الشكل الحالي مُورّثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | يعيد صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة افتراضيًا. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يعيد صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على حدود الشكل البصرية المحسوبة من محتواه المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GraphicalObject](../graphicalobject)
* واجهة [IZoomObject](../izoomobject)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->