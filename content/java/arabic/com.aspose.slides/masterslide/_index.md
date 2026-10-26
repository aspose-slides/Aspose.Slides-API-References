---
title: MasterSlide
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل شريحة رئيسية في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/masterslide/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

يمثل شريحة رئيسية في عرض تقديمي.
## الطرق

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع مدير HeaderFooter للشريحة الرئيسة. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | ينشئ شريحة رئيسية جديدة بناءً على الحالية، ويطبق سمة خارجية عليها، ثم يطبق الشريحة الرئيسية التي تم إنشاؤها على جميع الشرائح التابعة. |
| [getTitleStyle()](#getTitleStyle--) | يرجع نمط نص العنوان. |
| [getBodyStyle()](#getBodyStyle--) | يرجع نمط نص الجسم. |
| [getOtherStyle()](#getOtherStyle--) | يرجع نمط نص آخر. |
| [getLayoutSlides()](#getLayoutSlides--) | يرجع مجموعة الشرائح التخطيطية الفرعية لهذه الشريحة الرئيسة. |
| [getPreserve()](#getPreserve--) | يحدد ما إذا كانت الشريحة الرئيسة المقابلة تُحذف عندما تُحذف جميع الشرائح التي تلي تلك الشريحة الرئيسة. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | يحدد ما إذا كانت الشريحة الرئيسة المقابلة تُحذف عندما تُحذف جميع الشرائح التي تلي تلك الشريحة الرئيسة. |
| [getDependingSlides()](#getDependingSlides--) | يرجع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة الرئيسة. |
| [hasDependingSlides()](#hasDependingSlides--) | يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسة. |
| [getThemeManager()](#getThemeManager--) | يرجع مدير السمة. |
| [getName()](#getName--) | يرجع أو يضبط اسم الشريحة الرئيسة. |
| [setName(String value)](#setName-java.lang.String-) | يرجع أو يضبط اسم الشريحة الرئيسة. |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان ينبغي إظهار الأشكال على الشريحة الرئيسة في الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان ينبغي إظهار الأشكال على الشريحة الرئيسة في الشرائح أم لا. |
| [getDrawingGuides()](#getDrawingGuides--) | يرجع مجموعة من أدلة الرسم للشريحة الرئيسة. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

يرجع مدير HeaderFooter للشريحة الرئيسة. للقراءة فقط [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**القيمة المرجعة:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

ينشئ شريحة رئيسية جديدة استنادًا إلى الحالية، ويطبق سمة خارجية عليها، ثم يطبق الشريحة الرئيسية التي تم إنشاؤها على جميع الشرائح التابعة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | مسار ملف السمة الخارجي (.thmx). |

**القيمة المرجعة:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide جديد ذو سمة.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

يرجع نمط نص العنوان. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**القيمة المرجعة:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

يرجع نمط نص الجسم. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**القيمة المرجعة:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

يرجع نمط نص آخر. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**القيمة المرجعة:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

يرجع مجموعة الشرائح التخطيطية الفرعية لهذه الشريحة الرئيسة. للقراءة فقط [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

يمكنك الوصول إلى واجهة برمجة التطبيقات البديلة لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط باستخدام الخاصية ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) .

**القيمة المرجعة:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

يحدد ما إذا كانت الشريحة الرئيسة المقابلة تُحذف عندما تُحذف جميع الشرائح التي تلي تلك الشريحة الرئيسة. ملاحظة: Aspose.Slides لن يقوم أبدًا بإزالة أي شريحة رئيسية غير مستخدمة بمفرده، لإزالة الشرائح الرئيسة غير المستخدمة فعليًا استدعِ [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) قراءة/كتابة boolean .

**القيمة المرجعة:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

يحدد ما إذا كانت الشريحة الرئيسة المقابلة تُحذف عندما تُحذف جميع الشرائح التي تلي تلك الشريحة الرئيسة. ملاحظة: Aspose.Slides لن يقوم أبدًا بإزالة أي شريحة رئيسية غير مستخدمة بمفرده، لإزالة الشرائح الرئيسة غير المستخدمة فعليًا استدعِ [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) قراءة/كتابة boolean .

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

يرجع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة الرئيسة.

**القيمة المرجعة:**
com.aspose.slides.ISlide[] - مصفوفة من [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسة. للقراءة فقط boolean .

**القيمة المرجعة:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

يرجع مدير السمة. للقراءة فقط [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**القيمة المرجعة:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

يرجع أو يضبط اسم الشريحة الرئيسة. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

يرجع أو يضبط اسم الشريحة الرئيسة. قراءة/كتابة String.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسة في الشرائح أم لا. بالنسبة للشريحة الرئيسة نفسها، هذه الخاصية دائمًا تُرجع false. قراءة/كتابة boolean .

**القيمة المرجعة:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسة في الشرائح أم لا. بالنسبة للشريحة الرئيسة نفسها، هذه الخاصية دائمًا تُرجع false. قراءة/كتابة boolean .

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

يرجع مجموعة من أدلة الرسم للشريحة الرئيسة. للقراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // إضافة دليل الرسم العمودي الجديد إلى يمين مركز الشريحة
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)