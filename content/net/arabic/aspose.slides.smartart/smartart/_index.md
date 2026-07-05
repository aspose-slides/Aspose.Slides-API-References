---
title: SmartArt
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل مخطط SmartArt
type: docs
weight: 10600
url: /ar/aspose.slides.smartart/smartart/
---
## SmartArt فئة

يمثل مخطط SmartArt

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | يرجع مجموعات جميع العقد في كائن SmartArt. للقراءة فقط [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يرجع أو يعيّن النص البديل المرتبط بالشكل. للقراءة/الكتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يرجع أو يعيّن عنوان النص البديل المرتبط بالشكل. للقراءة/الكتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. للقراءة/الكتابة [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | يرجع أو يعيّن نمط اللون لكائن SmartArt. للقراءة/الكتابة [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يرجع عدد مواقع الاتصال على الشكل. للقراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يرجع بيانات مخصصة للشكل. للقراءة فقط [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص تأثير. للقراءة فقط [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص تعبئة. للقراءة فقط [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يرجع أو يعيّن خصائص إطار الشكل. للقراءة/الكتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | يرجع أقفال الشكل. للقراءة فقط [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يرجع أو يعيّن ارتفاع الشكل، مقاسًا بنقاط. للقراءة/الكتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. للقراءة/الكتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يرجع أو يعيّن الارتباط التشعبي المحدد للنقر بالفأرة. للقراءة/الكتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يرجع مدير الارتباط التشعبي. للقراءة فقط [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يرجع أو يعيّن الارتباط التشعبي المحدد للتمرير فوق الفأرة. للقراءة/الكتابة [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يرجع أو يعيّن خيار 'وضع علامة كزخرف'. للقراءة/الكتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | يرجع أو يعيّن حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. للقراءة/الكتابة Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | يرجع أو يعيّن تخطيط كائن SmartArt. للقراءة/الكتابة [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص خط. للقراءة فقط [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يرجع أو يعيّن اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. للقراءة/الكتابة String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | يرجع مجموعات العقد الجذرية في كائن SmartArt. للقراءة فقط [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يرجع معرفًا فريدًا محدودًا بالشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند. للقراءة فقط UInt32. انظر أيضًا [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يرجع كائن GroupShape الأب إذا كان الشكل مُجَمَّعًا. وإلا يرجع null. للقراءة فقط [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يرجع العنصر النائب للشكل. يرجع null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يرجع عرض الشرائح الأب لشريحة. للقراءة فقط [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | يرجع أو يعيّن النمط السريع لكائن SmartArt. للقراءة/الكتابة [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يرجع أو يعيّن خصائص إطار الشكل الخام. للقراءة/الكتابة [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يرجع أو يعيّن عدد الدرجات التي يتم فيها تدوير الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس عقارب الساعة. للقراءة/الكتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | يرجع أقفال الشكل. للقراءة فقط [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 خصائص) |
| [Slide](../../aspose.slides/shape/slide) { get; } | يرجع الشريحة الأب لشكل. للقراءة فقط [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يرجع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. للقراءة فقط [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يرجع معرفًا داخليًا محدودًا بالعرض مخصصًا للاستخدام من قبل الإضافات أو كود آخر. نظرًا لأن هذه القيمة يمكن أن يعيد تخصيصها المستخدم أو برمجيًا، يجب عدم التعامل معها كمفتاح فريد دائم. للقراءة فقط UInt32. انظر également [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | يرجع أو يعيّن عرض الشكل، مقاسًا بنقاط. للقراءة/الكتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يرجع أو يعيّن إحداثي x لزاوية الشكل العليا اليسرى، مقاسًا بنقاط. للقراءة/الكتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يرجع أو يعيّن إحداثي y لزاوية الشكل العليا اليسرى، مقاسًا بنقاط. للقراءة/الكتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يرجع موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z. للقراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى واحد محدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسة التي يرث منها الشكل الحالي). يتم إرجاع null إذا لم يكن الشكل الحالي مُرثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | يرجع صورة مصغرة للشكل. يتم استخدام النوع ShapeThumbnailBounds.Shape للحدود الافتراضية للصورة المصغرة. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يرجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يرجع حدود الشكل البصرية المحسوبة من محتواه المُعرض. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GraphicalObject](../../aspose.slides/graphicalobject)
* واجهة [ISmartArt](../ismartart)
* مساحة الاسم [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->