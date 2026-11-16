---
title: ZoomFrame
second_title: مرجع API لـ Aspose.Sildes for .NET
description: يمثل كائن Slide Zoom داخل شريحة.
type: docs
weight: 11860
url: /ar/aspose.slides/zoomframe/
---
## فئة ZoomFrame

يمثل كائن Slide Zoom داخل شريحة.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | تُرجِع أو تُعيّن النص البديل المرتبط بصورة. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | تُرجِع أو تُعيّن عنوان النص البديل المرتبط بصورة. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض صورة في وضع العرض بالأبيض والأسود.. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تُرجِع عدد مواقع الاتصال على الصورة. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | تُرجِع البيانات المخصصة للصورة. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | تُرجِع كائن EffectFormat الذي يحتوي على تأثيرات بكسل مطبقة على الصورة. ملاحظة: قد تُعيد null لبعض أنواع الصور التي لا تملك خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | تُرجِع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للصورة. ملاحظة: قد تُعيد null لبعض أنواع الصور التي لا تملك خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | تُرجِع أو تُعيّن خصائص إطار الصورة. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | تُرجِع أقفال الصورة. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | تُحصل أو تُعيّن ارتفاع الصورة، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحدد ما إذا كانت الصورة مخفية. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | تُرجِع أو تُعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | تُرجِع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | تُرجِع أو تُعيّن الارتباط التشعبي المحدد عند مرور الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | تُحصل أو تُعيّن نوع الصورة لكائن Zoom. قراءة/كتابة [`ZoomImageType`](../zoomimagetype). القيمة الافتراضية: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | تُحصل أو تُعيّن خيار 'Mark as decorative'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحدد ما إذا كانت الصورة مُجمَّعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحدد ما إذا كانت الصورة من نوع TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | تُرجِع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للصورة. ملاحظة: قد تُعيد null لبعض أنواع الصور التي لا تملك خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | تُرجِع أو تُعيّن اسم الصورة. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | تُرجِع معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الصورة ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الصورة من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | تُرجِع كائن GroupShape الأصل إذا كانت الصورة مُجمَّعة. وإلا تُعيد null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | تُرجِع العنصر النائب للصورة. تُعيد null إذا لم يكن للصورة عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | تُرجِع العرض التقديمي الأصل للشريحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | تُرجِع أو تُعيّن خصائص إطار الصورة الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | تُحصل أو تُعيّن سلوك التنقل في عرض الشرائح. قراءة/كتابة Boolean. القيمة الافتراضية: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تُرجِع أو تُعيّن عدد الدرجات التي تدور فيها الصورة المحددة حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | تُرجِع أقفال الصورة. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 خصائص) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | تُحصل أو تُعيّن قيمة تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. قراءة/كتابة Boolean. القيمة الافتراضية: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | تُرجِع شريحة الأصل للصورة. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | تُحصل أو تُعيّن كائن الشريحة الذي يرتبط به كائن Slide Zoom. قراءة/كتابة [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | تُرجِع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للصورة. ملاحظة: قد تُعيد null لبعض أنواع الصور التي لا تملك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | تُحصل أو تُعيّن مدة الانتقال بين Zoom والشريحة. قراءة/كتابة Single. القيمة الافتراضية: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | تُرجِع معرفًا داخليًا يخص العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو كود آخر. نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجياً، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | تُحصل أو تُعيّن عرض الصورة، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | تُحصل أو تُعيّن إحداثي x للزاوية العلوية اليسرى للصورة، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | تُحصل أو تُعيّن إحداثي y للزاوية العلوية اليسرى للصورة، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | تُحصل أو تُعيّن صورة لكائن Zoom. قراءة/كتابة [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | تُرجِع موضع الصورة في ترتيب z. Shapes[0] تُعيد الصورة في الخلفية، وShapes[Shapes.Count - 1] تُعيد الصورة في المقدمة. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى واحد محدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | تُرجِع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسة التي يرث منها الشكل الحالي). تُرجَع null إذا لم يكن الشكل الحالي موروثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | تُرجِع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تُرجِع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | تُحصل على حدود الشكل البصرية المحسوبة من محتواه المُعرض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يُحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [ZoomObject](../zoomobject)
* واجهة [IZoomFrame](../izoomframe)
* مساحة اسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->