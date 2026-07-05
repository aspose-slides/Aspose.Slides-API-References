---
title: Table
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل جدولًا على شريحة.
type: docs
weight: 10860
url: /ar/aspose.slides/table/
---
## فئة Table

يمثل جدولًا على شريحة.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## الخصائص

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | إرجاع أو تعيين النص البديل المرتبط بشكّل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | إرجاع أو تعيين عنوان النص البديل المرتبط بشكّل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | تحدد الخاصية كيف سيظهر الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | إرجاع مجموعة الأعمدة. قراءة فقط [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | إرجاع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | إرجاع بيانات الشكل المخصصة. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | إرجاع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | إرجاع كائن TableFormat.FillFormat الذي يحتوي على تنسيق التعبئة للجدول. قراءة فقط [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | يحدد ما إذا كان يجب رسم العمود الأول للجدول بتنسيق خاص. قراءة/كتابة Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | يحدد ما إذا كان يجب رسم الصف الأول للجدول بتنسيق خاص. قراءة/كتابة Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | إرجاع أو تعيين ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | إرجاع أو تعيين الارتباط الفائق المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | إرجاع مدير الارتباط الفائق. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | إرجاع أو تعيين الارتباط الفائق المحدد للتمرير فوق الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | إرجاع أو تعيين خيار "وضع علامة كزخرفة". قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | إرجاع الخلية عند فهارس العمود والصف المحددين. قراءة فقط [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | يحدد ما إذا كان يجب رسم العمود الأخير للجدول بتنسيق خاص. قراءة/كتابة Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | يحدد ما إذا كان يجب رسم الصف الأخير للجدول بتنسيق خاص. قراءة/كتابة Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُعيد null لبعض أنواع الأشكال التي لا تمتلك خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | إرجاع أو تعيين اسم الشكل. يجب ألا يكون null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | إرجاع معرف فريد نطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | إرجاع كائن GroupShape الأم إذا كان الشكل مجموعة. وإلا يُعيد null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | إرجاع العنصر النائب للشكل. يُعيد null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | إرجاع العرض التقديمي الأم للشفرة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. قراءة/كتابة Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | إرجاع أو تعيين عدد الدرجات التي يُدوَّر فيها الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ السالبة إلى عكسها. قراءة/كتابة Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | إرجاع مجموعة الصفوف. قراءة فقط [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | إرجاع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 خصائص) |
| [Slide](../../aspose.slides/shape/slide) { get; } | إرجاع الشريحة الأم للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | إرجاع أو تعيين نمط جدول مدمج. قراءة/كتابة [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | إرجاع كائن TableFormat الذي يحتوي على خصائص تنسيق هذا الجدول. قراءة فقط [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد null لبعض الأنواع التي لا تمتلك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | إرجاع معرف داخلي نطاق العرض مخصص للاستخدام من قبل الملحقات أو الكود الآخر. بما أن هذا القيم يمكن إعادة تعيينه من قبل المستخدم أو برمجيًا، لا يجب اعتباره مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. قراءة/كتابة Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | إرجاع أو تعيين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | إرجاع أو تعيين إحداثي x للركن العلوي الأيسر للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | إرجاع أو تعيين إحداثي y للركن العلوي الأيسر للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | إرجاع موضع الشكل في ترتيب الـ z. Shapes[0] تُعيد الشكل في مؤخرة ترتيب الـ z، و Shapes[Shapes.Count - 1] تُعيد الشكل في مقدمة ترتيب الـ z. قراءة فقط Int32. |

## الطرق

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى القيم المحددة. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | إرجاع شكل عنصر نائب أساسي (شكل من تخطيط أو شريحة رئيسية يتم وراثته من قبل الشكل الحالي). يُعيد null إذا لم يكن الشكل الحالي مُورَّثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | إرجاع صورة مصغرة للشكل. يستخدم النوع ShapeThumbnailBounds.Shape كقيمة افتراضية. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | إرجاع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | الحصول على الحدود البصرية للشكل محسوبة من محتواه المُعروض. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | دمج الخلايا المجاورة. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعريف أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | ضبط خصائص تنسيق الفقرة المحددة على جميع فقرات خلايا الجدول. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | ضبط خصائص تنسيق الجزء المحدد على جميع أجزاء خلايا الجدول. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | ضبط خصائص تنسيق إطار النص المحدد على جميع إطارات نص خلايا الجدول. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | حفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | حفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GraphicalObject](../graphicalobject)
* واجهة [ITable](../itable)
* نطاق أسماء [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->