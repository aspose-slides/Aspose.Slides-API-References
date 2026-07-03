---
title: LegacyDiagram
second_title: مرجع API لتطبيق Aspose.Sildes للـ .NET
description: يمثل كائن مخطط قديم.
type: docs
weight: 7670
url: /ar/aspose.slides/legacydiagram/
---
## LegacyDiagram فئة

Represents a legacy diagram object.

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يعيد أو يحدد النص البديل المرتبط بشكِل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يعيد أو يحدد عنوان النص البديل المرتبط بشكِل. قراءة/كتابة String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | يسمح بالحصول على واجهة IGraphicalObject الأساسية. قراءة فقط [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | المِلكية تحدد كيف سيُظهر الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يعيد عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يعيد البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يعيد أو يحدد خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | يعيد أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحصل أو يحدد ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يعيد أو يحدد الارتباط التشعبي المحدد للنقر بالماوس. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يعيد مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يعيد أو يحدد الارتباط التشعبي المحدد للتمرير فوق الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحصل أو يحدد خيار 'Mark as decorative'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يعيد أو يحدد اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يعيد معرفًا فريدًا محصورًا بالشرائح يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يُعيد null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يعيد العنصر النائب للشكل. يُعيد null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يعيد العرض الرئيسي للشرائح. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يعيد أو يحدد خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يعيد أو يحدد عدد درجات دوران الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | يعيد أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (خاصيتان) |
| [Slide](../../aspose.slides/shape/slide) { get; } | يعيد الشريحة الأم للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير الثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يعيد معرفًا داخليًا محصورًا بالعرض مخصصًا لاستخدام الإضافات أو كود آخر. بما أن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحصل أو يحدد عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحصل أو يحدد إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحصل أو يحدد إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يعيد موضع الشكل في ترتيب z. Shapes[0] تُعيد الشكل في الخلف من ترتيب z، وShapes[Shapes.Count - 1] تُعيد الشكل في المقدمة من ترتيب z. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى المحدد. |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | يحوّل المخطط legacy إلى مجموعة أشكال قابلة للتحرير. يضيف كائن GroupShape المنشأ إلى مجموعة الأشكال الأم في نفس الموقع. |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | يحوّل المخطط legacy إلى كائن SmartArt قابل للتحرير. يضيف كائن SmartArt المنشأ إلى مجموعة الأشكال الأم في نفس الموقع. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسة التي يرث منها الشكل الحالي). يُعيد null إذا لم يكن الشكل الحالي موروثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | يعيد صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يعيد صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* class [GraphicalObject](../graphicalobject)
* interface [ILegacyDiagram](../ilegacydiagram)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->