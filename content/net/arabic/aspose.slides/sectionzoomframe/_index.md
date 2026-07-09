---
title: SectionZoomFrame
second_title: مرجع API الخاص بـ Aspose.Sildes لـ .NET
description: يمثل كائن Section Zoom في شريحة.
type: docs
weight: 9780
url: /ar/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame الصنف

يمثل كائن Section Zoom في شريحة.

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يرجع أو يضبط النص البديل المرتبط بشكِل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يرجع أو يضبط عنوان النص البديل المرتبط بشكِل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يرجع عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يرجع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يرجع أو يضبط خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | يرجع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحصل أو يضبط ارتفاع الشكل، مقاساً بنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفياً. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يرجع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يرجع أو يضبط الارتباط التشعبي المحدد لتمرير الفأرة فوقه. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | يحصل أو يضبط نوع الصورة لكائن Zoom. قراءة/كتابة [`ZoomImageType`](../zoomimagetype). القيمة الافتراضية: معاينة |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحصل أو يضبط خيار “وضع علامة كزخرف”. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يرجع أو يضبط اسم الشكل. يجب ألا يكون فارغاً. استخدم سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يرجع معرفًا فريدًا محصورًا في الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. راجع أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يرجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يرجع العنصر النائب للشكل. يرجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يرجع العرض التقديمي الأب للشريحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يرجع أو يضبط خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | يحصل أو يضبط سلوك التنقل في عرض الشرائح. قراءة/كتابة Boolean. القيمة الافتراضية: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يرجع أو يضبط عدد الدرجات التي يدور فيها الشكل حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | يرجع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (خاصيتان) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | يحصل أو يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. قراءة/كتابة Boolean. القيمة الافتراضية: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | يرجع الشريحة الأب للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | يحصل أو يضبط كائن القسم الذي يرتبط به كائن Section Zoom. قراءة/كتابة [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يرجع كائن ThreeDFormat الذي يحتوي على خصائص تأثير 3D للشكل. ملاحظة: قد يرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص 3D. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | يحصل أو يضبط مدة الانتقال بين Zoom والشريحة. قراءة/كتابة Single. القيمة الافتراضية: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يرجع معرفًا داخليًا محصورًا في العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. بما أن هذا المعرف يمكن إعادة تعيينه من قبل المستخدم أو برمجيًا، لا يجب اعتباره مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. راجع أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحصل أو يضبط عرض الشكل، مقاساً بنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحصل أو يضبط الإحداثي x لزاوية الشكل العلوية اليسرى، مقاساً بنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحصل أو يضبط الإحداثي y لزاوية الشكل العلوية اليسرى، مقاساً بنقاط. قراءة/كتابة Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | يحصل أو يضبط الصورة لكائن Zoom. قراءة/كتابة [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يرجع موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل في الخلف من ترتيب z، و Shapes[Shapes.Count - 1] يرجع الشكل في المقدمة. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى ما تم تحديده. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يرجع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو الشريحة الرئيسية التي يرثها الشكل الحالي). يرجع null إذا لم يكن الشكل الحالي مُورَّثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | يرجع صورة مصغرة للشكل. يستخدم النوع ShapeThumbnailBounds.Shape كقيمة افتراضية. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المُرضى. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* الصنف [ZoomObject](../zoomobject)
* الواجهة [ISectionZoomFrame](../isectionzoomframe)
* نطاق الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->