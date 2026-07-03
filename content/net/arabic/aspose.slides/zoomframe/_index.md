---
title: ZoomFrame
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل كائن Slide Zoom في شريحة.
type: docs
weight: 11840
url: /ar/aspose.slides/zoomframe/
---
## ZoomFrame الفئة

Represents a Slide Zoom object in a slide.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## الخصائص

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | إرجاع أو تعيين النص البديل المرتبط بشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | إرجاع أو تعيين عنوان النص البديل المرتبط بشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | إرجاع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | إرجاع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | إرجاع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | إرجاع أو تعيين ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحديد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | إرجاع مدير الارتباطات التشعبية. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | إرجاع أو تعيين الارتباط التشعبي المحدد لتحوم الفأرة فوقه. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | إرجاع أو تعيين نوع الصورة لكائن التكبير. قراءة/كتابة [`ZoomImageType`](../zoomimagetype). القيمة الافتراضية: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | إرجاع أو تعيين خيار 'وضع علامة كديكور'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحديد ما إذا كان الشكل مُجَمَّعًا. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحديد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | إرجاع أو تعيين اسم الشكل. يجب ألا يكون فارغًا. استخدم سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | إرجاع معرف فريد محصور في الشريحة يظل ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود interop بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | إرجاع كائن GroupShape الأب إذا كان الشكل مُجَمَّعًا. وإلا يُرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | إرجاع العنصر النائب للشكل. يُرجع null إذا لم يحتوي الشكل على عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | إرجاع العرض التقديمي الأب للشريحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | إرجاع أو تعيين سلوك التنقل في عرض الشرائح. قراءة/كتابة Boolean. القيمة الافتراضية: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | إرجاع أو تعيين عدد الدرجات التي يُدوَّر بها الشكل حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السلبية تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (خاصيتان) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | إرجاع أو تعيين قيمة تحدد ما إذا كان التكبير سيستخدم خلفية الشريحة الهدف. قراءة/كتابة Boolean. القيمة الافتراضية: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | إرجاع الشريحة الأب للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | إرجاع أو تعيين كائن الشريحة الذي يرتبط به كائن Slide Zoom. قراءة/كتابة [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | إرجاع أو تعيين مدة الانتقال بين التكبير والشريحة. قراءة/كتابة Single. القيمة الافتراضية: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | إرجاع معرف داخلي محصور في العرض التقديمي مخصص للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | إرجاع أو تعيين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | إرجاع أو تعيين إحداثي x لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | إرجاع أو تعيين إحداثي y لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | إرجاع أو تعيين صورة لكائن التكبير. قراءة/كتابة [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | إرجاع موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل في الخلف، و Shapes[Shapes.Count - 1] يرجع الشكل في المقدمة. قراءة فقط Int32. |

## الأساليب

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | إرجاع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي موروثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | إرجاع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | إرجاع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | إرجاع حدود الشكل البصرية المحسوبة من محتواه المُعرض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* الفئة [ZoomObject](../zoomobject)
* الواجهة [IZoomFrame](../izoomframe)
* نطاق الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->