---
title: OleObjectFrame
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل كائن OLE على شريحة.
type: docs
weight: 9230
url: /ar/aspose.slides/oleobjectframe/
---
## فئة OleObjectFrame

يمثل كائن OLE في شريحة.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ترجع أو تعين النص البديل المرتبط بشكل. قراءة/كتابة String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ترجع أو تعين عنوان النص البديل المرتبط بشكل. قراءة/كتابة String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | يسمح بالحصول على واجهة IGraphicalObject الأساسية. قراءة فقط [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | الخاصية تحدد كيف سيُعرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ترجع عدد مواقع الاتصال على الشكل. قراءة فقط Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ترجع البيانات المخصصة للشكل. قراءة فقط [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | إرجاع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يرجع null لبعض أنواع الأشكال التي لا تملك خصائص تأثير. قراءة فقط [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | تحصل أو تعين معلومات حول بيانات OLE المدمجة. قراءة/كتابة [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | ترجع اسم ملف كائن OLE المدمج |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | ترجع مسار كائن OLE المدمج |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. ملاحظة: قد يرجع null لبعض الأنواع التي لا تملك خصائص تعبئة. قراءة فقط [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ترجع أو تعين خصائص إطار الشكل. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | ترجع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | تحصل أو تعين ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ترجع أو تعين الارتباط التشعبي المحدد للنقر بالماوس. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ترجع مدير الارتباط التشعبي. قراءة فقط [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ترجع أو تعين الارتباط التشعبي المحدد للماوس فوق. قراءة/كتابة [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | تحصل أو تعين خيار 'وضع علامة كزخرف' قراءة/كتابة Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تحدد ما إذا كان الشكل مجموعة. قراءة فقط Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | تحدد ما إذا كان الكائن مرئيًا كأيقونة. قراءة/كتابة Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | تحدد ما إذا كان الكائن مرتبطًا بملف خارجي. قراءة فقط Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تحدد ما إذا كان الشكل هو TextHolder_PPT. قراءة فقط Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: قد يرجع null لبعض الأنواع التي لا تملك خصائص خط. قراءة فقط [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | ترجع المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف القصير. قراءة فقط String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | ترجع المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف الطويل. قراءة/كتابة String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | ترجع المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا ترجع سلسلة فارغة. قراءة فقط String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | ترجع أو تعين اسم الشكل. يجب أن لا يكون null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | ترجع أو تعين اسم الكائن. قراءة/كتابة String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | ترجع ProgID الكائن. قراءة فقط String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ترجع معرفًا فريدًا ضمن الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط UInt32. انظر أيضًا [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ترجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا ترجع null. قراءة فقط [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ترجع العنصر النائب للشكل. ترجع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ترجع عرض الشرائح الأب للشريحة. قراءة فقط [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ترجع أو تعين خصائص إطار الشكل الخام. قراءة/كتابة [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ترجع أو تعين عدد الدرجات التي يدورها الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس عقارب الساعة. قراءة/كتابة Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | ترجع أقفال الشكل. قراءة فقط [`IGraphicalObjectLock`](../igraphicalobjectlock). (خاصيتان) |
| [Slide](../../aspose.slides/shape/slide) { get; } | ترجع الشريحة الأب للشكل. قراءة فقط [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | ترجع كائن خصائص تعبئة صورة OleObject. قراءة فقط [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | ترجع أو تعين العنوان لأيقونة OleObject. قراءة/كتابة String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يرجع null لبعض الأنواع التي لا تملك خصائص ثلاثية الأبعاد. قراءة فقط [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ترجع معرفًا داخليًا ضمن العرض مخصصًا للاستخدام من قبل الإضافات أو كود آخر. نظرًا لأنه يمكن إعادة تعيينه من قبل المستخدم أو برمجيًا، لا يجب اعتباره مفتاحًا فريدًا دائمًا. قراءة فقط UInt32. انظر أيضًا [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | تحدد ما إذا كان الكائن المدمج المرتبط يتم تحديثه تلقائيًا عند فتح العرض أو طباعته. قراءة/كتابة Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | تحصل أو تعين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | تحصل أو تعين الإحداثي السيني للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | تحصل أو تعين الإحداثي الصادي للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | إرجاع موضع الشكل في ترتيب z. Shapes[0] تُرجع الشكل في الخلف من ترتيب z، و Shapes[Shapes.Count - 1] تُرجع الشكل في المقدمة. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يوجد ويضبط خصائص العنصر النائب إلى المحدد. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ترجع شكل عنصر نائب أساسي (شكل من التخطيط أو الشريحة الرئيسية التي يرث منها الشكل الحالي). تُرجع null إذا لم يكن الشكل الحالي مورّثًا. |
| [GetImage](../../aspose.slides/shape/getimage)() | ترجع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة بشكل افتراضي. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ترجع صورة مصغرة للشكل. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | تحصل على حدود الشكل البصرية المحسوبة من محتواه المرسوم. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | يضبط معلومات حول بيانات OLE المدمجة. يغيّر هذا الأسلوب خصائص الكائن لتطابق البيانات الجديدة ويضبط علامة IsObjectLink إلى false، مما يدل على أن كائن OLE مدمج. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | يحفظ محتوى الشكل كملف SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | يحفظ محتوى الشكل كملف SVG. |

### أمثلة

المثال التالي يوضح كيفية الوصول إلى إطارات كائن OLE.

```csharp
[C#]
// يحمل ملف PPTX إلى كائن عرض تقديمي
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // يصل إلى الشريحة الأولى
    ISlide sld = pres.Slides[0];
    // يحول الشكل إلى OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // يقرأ كائن OLE ويكتبها إلى القرص
    if (oleObjectFrame != null)
    {
        // يحصل على بيانات الملف المدمج
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // يحصل على امتداد الملف المدمج
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // ينشئ مسارًا لحفظ الملف المستخرج
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // يحفظ البيانات المستخرجة
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### انظر أيضًا

* فئة [GraphicalObject](../graphicalobject)
* واجهة [IOleObjectFrame](../ioleobjectframe)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->