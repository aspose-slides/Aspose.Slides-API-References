---
title: Table
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل جدولًا على شريحة.
type: docs
weight: 10880
url: /ar/aspose.slides/table/
---
## فئة Table

يمثل جدولاً على شريحة.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | يعيد أو يضبط النص البديل المرتبط بشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | يعيد أو يضبط عنوان النص البديل المرتبط بشكل. قراءة/كتابة String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الممتلكات تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | يعيد مجموعة الأعمدة. قراءة فقط [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | يعيد عدد نقاط الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | يعيد البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تملك خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | يعيد كائن TableFormat.FillFormat الذي يحتوي على تنسيق التعبئة للجدول. قراءة فقط [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | يحدد ما إذا كان يجب رسم العمود الأول للجدول بتنسيق خاص. قراءة/كتابة Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | يحدد ما إذا كان يجب رسم الصف الأول للجدول بتنسيق خاص. قراءة/كتابة Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | يعيد أو يضبط خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | يعيد أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | يعيد أو يضبط ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | يعيد مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | يعيد أو يضبط الارتباط التشعبي المحدد للتمرير فوق الفأرة. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | يعيد أو يضبط خيار 'تحديد كديكوري' قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | يحدد ما إذا كان الشكل ضمن مجموعة. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | يحدد ما إذا كان الشكل هو TextHolder_PPT. قراءة فقط Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | يعيد الخلية عند الفهارس المحددة للعمود والصف. قراءة فقط [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | يحدد ما إذا كان يجب رسم العمود الأخير للجدول بتنسيق خاص. قراءة/كتابة Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | يحدد ما إذا كان يجب رسم الصف الأخير للجدول بتنسيق خاص. قراءة/كتابة Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تملك خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | يعيد أو يضبط اسم الشكل. يجب ألا يكون null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | يعيد معرفًا فريدًا محصورًا بالعرض يظل ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل بشكل موثوق من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | يعيد كائن GroupShape الأصلي إذا كان الشكل ضمن مجموعة. وإلا يرجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | يعيد العنصر النائب للشكل. يرجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | يعيد العرض الأصل للشرائح. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | يعيد أو يضبط خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. قراءة/كتابة Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | يعيد أو يضبط عدد الدرجات التي يدور فيها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. قراءة/كتابة Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | يعيد مجموعة الصفوف. قراءة فقط [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | يعيد أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 خصائص) |
| [Slide](../../aspose.slides/shape/slide) { get; } | يعيد الشريحة الأصل للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | يعيد أو يضبط نمط الجدول المدمج. قراءة/كتابة [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | يعيد كائن TableFormat الذي يحتوي على خصائص التنسيق لهذا الجدول. قراءة فقط [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: يمكن أن يرجع null لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | يعيد معرفًا داخليًا محصورًا بالعرض مخصصًا للاستخدام بواسطة الإضافات أو كود آخر. بما أن هذه القيمة يمكن أن يعيد تعيينها من قبل المستخدم أو برمجيًا، لا يجب اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. قراءة/كتابة Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | يعيد أو يضبط عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | يعيد أو يضبط إحداثي س للمربع العلوي الأيسر للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | يعيد أو يضبط إحداثي ص للمربع العلوي الأيسر للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | يعيد موقع الشكل في ترتيب z. Shapes[0] يرجع الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | يعيد شكل عنصر نائب أساسي (شكل من التصميم و/أو الشريحة الرئيسة التي يُورّث منها الشكل الحالي). يرجع null إذا لم يكن الشكل الحالي مُورّثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | يعيد صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كنوع حدود الصورة المصغرة افتراضيًا. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | يعيد صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | يعيد حدود الشكل البصرية المحسوبة من محتواه المُرَسَم. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | يدمج الخلايا المجاورة. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يعرف أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | يضبط خصائص تنسيق الفقرة المحددة على جميع فقرات خلايا الجدول. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | يضبط خصائص تنسيق الجزء المحدد على جميع أجزاء خلايا الجدول. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | يضبط خصائص تنسيق إطار النص المحددة على جميع إطارات نص خلايا الجدول. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### انظر أيضًا

* فئة [GraphicalObject](../graphicalobject)
* واجهة [ITable](../itable)
* مساحة أسماء [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->