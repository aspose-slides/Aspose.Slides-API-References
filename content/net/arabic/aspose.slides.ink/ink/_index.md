---
title: Ink
second_title: مرجع API Aspose.Sildes لـ .NET
description: يمثل كائن حبر على شريحة.
type: docs
weight: 7570
url: /ar/aspose.slides.ink/ink/
---
## فئة Ink

يمثل كائن حبر على الشريحة.

```csharp
public class Ink : GraphicalObject, IInk
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | تُرجع أو تُعيّن النص البديل المرتبط بشكّل. قابلة للقراءة والكتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | تُرجع أو تُعيّن عنوان النص البديل المرتبط بشكّل. قابلة للقراءة والكتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قابلة للقراءة والكتابة [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تُرجع عدد نقاط الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | تُرجع البيانات المخصصة للشكل. للقراءة فقط [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | تُرجع كائن EffectFormat الذي يحتوي على تأثيرات بكسل مطبّقة على الشكل. ملاحظة: قد تُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص تأثير. للقراءة فقط [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | تُرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. ملاحظة: قد تُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص تعبئة. للقراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | تُرجع أو تُعيّن خصائص إطار الشكل. قابلة للقراءة والكتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | تُرجع أقفال الشكل. للقراءة فقط [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | تُعيد أو تُعيّن ارتفاع الشكل، مقاسًا بالنقاط. قابلة للقراءة والكتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحدد ما إذا كان الشكل مخفيًا. قابلة للقراءة والكتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | تُرجع أو تُعيّن الرابط التشعبي المحدد للنقر بالماوس. قابلة للقراءة والكتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | تُرجع مدير الروابط التشعبية. للقراءة فقط [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | تُرجع أو تُعيّن الرابط التشعبي المحدد عند مرور الماوس. قابلة للقراءة والكتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | تُعيد أو تُعيّن خيار 'Mark as decorative' قابل للقراءة والكتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحدد ما إذا كان الشكل مجموعة. للقراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | تُرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: قد تُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص خط. للقراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | تُرجع أو تُعيّن اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قابلة للقراءة والكتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | تُرجع مُعرّفًا فريدًا محصورًا بالشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل بموثوقية من أي مكان في المستند. للقراءة فقط UInt32. أنظر أيضًا [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | تُرجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا تُعيد null. للقراءة فقط [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | تُرجع العنصر النائب للشكل. تُعيد null إذا لم يمتلك الشكل عنصرًا نائبًا. للقراءة فقط [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | تُرجع العرض التقديمي الأب للشريحة. للقراءة فقط [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | تُرجع أو تُعيّن خصائص إطار الشكل الخام. قابلة للقراءة والكتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تُرجع أو تُعيّن عدد الدرجات التي يتم تدوير الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دورة باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دورة عكس اتجاه عقارب الساعة. قابلة للقراءة والكتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | تُرجع أقفال الشكل. للقراءة فقط [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (خاصيتان) |
| [Slide](../../aspose.slides/shape/slide) { get; } | تُرجع الشريحة الأب للشكل. للقراءة فقط [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | تُرجع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد تُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. للقراءة فقط [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | تُعيد جميع الآثار الموجودة في عنصر IInk [`IInkTrace`](../iinktrace). للقراءة فقط. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | تُرجع مُعرفًا داخليًا محصورًا بالعرض التقديمي مخصصًا للاستخدام من قِبل الإضافات أو كود آخر. نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجياً، لا ينبغي اعتبارها مفتاحًا فريدًا مستدامًا. للقراءة فقط UInt32. أنظر أيضًا [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | تُعيد أو تُعيّن عرض الشكل، مقاسًا بالنقاط. قابلة للقراءة والكتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | تُعيد أو تُعيّن إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قابلة للقراءة والكتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | تُعيد أو تُعيّن إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قابلة للقراءة والكتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | تُرجع موضع الشكل في ترتيب z. Shapes[0] تُعيد الشكل في مؤخرة ترتيب z، وShapes[Shapes.Count - 1] تُعيد الشكل في مقدمة ترتيب z. للقراءة فقط Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | تُعيد مجموعة الصور المخصصة المستخدمة لمحاكاة التأثيرات البصرية لفرش الحبر. تُستخدم هذه الصور عند عرض الحبر بقيم [`InkEffectType`](../inkeffecttype) محددة، مثل Galaxy، Rainbow، إلخ. من خلال توفير صورك الخاصة، يمكنك التحكم في مظهر كل تأثير حبر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | تُرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). تُعاد null إذا لم يكن الشكل الحالي موروثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | تُرجع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تُرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | تُعيد الحدود البصرية للشكل المحسوبة من محتواه المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يضبط أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### أنظر أيضًا

* الفئة [GraphicalObject](../../aspose.slides/graphicalobject)
* الواجهة [IInk](../iink)
* النطاق [Aspose.Slides.Ink](../../aspose.slides.ink)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->