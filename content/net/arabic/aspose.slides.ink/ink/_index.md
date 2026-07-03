---
title: Ink
second_title: مرجع API لـ Aspose.Sildes for .NET
description: يمثل كائن حبر على شريحة.
type: docs
weight: 7550
url: /ar/aspose.slides.ink/ink/
---
## Ink فئة

يمثل كائن حبر على شريحة.

```csharp
public class Ink : GraphicalObject, IInk
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يرجع أو يعيّن النص البديل المرتبط بشكله. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يرجع أو يعيّن عنوان النص البديل المرتبط بشكله. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يرجع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يرجع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد قيمة null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق الملء للشكل. ملاحظة: قد يُعيد قيمة null لبعض أنواع الأشكال التي لا تحتوي على خصائص ملء. قراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يرجع أو يعيّن خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | يرجع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يحصل أو يعيّن ارتفاع الشكل، مقاس بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يرجع أو يعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يرجع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يرجع أو يعيّن الارتباط التشعبي المحدد عند التمرير بالفأرة. قراءة/كتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يحصل أو يعيّن خيار 'Mark as decorative'. قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُعيد قيمة null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يرجع أو يعيّن اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يرجع معرفًا فريدًا محصورًا بالشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالرجوع إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يرجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يرجع null. قراءة فقط [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يرجع العنصر النائب للشكل. يرجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يرجع العرض التقديمي الأب للشريحة. قراءة فقط [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يرجع أو يعيّن خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يرجع أو يعيّن عدد الدرجات التي يدور بها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقربة الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقربة الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | يرجع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 خصائص) |
| [Slide](../../aspose.slides/shape/slide) { get; } | يرجع الشريحة الأب للشكل. قراءة فقط [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يرجع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد قيمة null لبعض أنواع الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | يحصل على جميع الآثار الموجودة في عنصر IInk [`IInkTrace`](../iinktrace). قراءة فقط. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يرجع معرفًا داخليًا محصورًا بالعرض التقديمي مخصصًا لاستخدام الإضافات أو كود آخر. نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يحصل أو يعيّن عرض الشكل، مقاس بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يحصل أو يعيّن إحداثي x لزاوية الشكل العليا اليسرى، مقاس بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يحصل أو يعيّن إحداثي y لزاوية الشكل العليا اليسرى، مقاس بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يرجع موضع الشكل في ترتيب z. Shapes[0] تُعيد الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] تُعيد الشكل في مقدمة ترتيب z. قراءة فقط Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | يحصل على مجموعة الصور المخصصة المستخدمة لمحاكاة التأثيرات البصرية لفرش الحبر. تُستخدم هذه الصور عند عرض الحبر بقيم [`InkEffectType`](../inkeffecttype) محددة، مثل Galaxy، Rainbow، إلخ. من خلال توفير صورك الخاصة، يمكنك التحكم في ظهور كل تأثير حبر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). يُرجع null إذا لم يكن الشكل الحالي موروثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | يرجع صورة مصغرة للشكل. يتم استخدام النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يحصل على حدود الشكل البصرية المحسوبة من المحتوى المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GraphicalObject](../../aspose.slides/graphicalobject)
* واجهة [IInk](../iink)
* مساحة اسم [Aspose.Slides.Ink](../../aspose.slides.ink)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->