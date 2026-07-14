---
title: MasterSlide
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
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

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | إرجاع مدير HeaderFooter للشريحة الرئيسة. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | إنشاء شريحة رئيسية جديدة بناءً على الحالية، مع تطبيق سمة خارجية عليها وتطبيق الشريحة الرئيسة التي تم إنشاؤها على جميع الشرائح التابعة. |
| [getTitleStyle()](#getTitleStyle--) | إرجاع نمط نص العنوان. |
| [getBodyStyle()](#getBodyStyle--) | إرجاع نمط نص المتن. |
| [getOtherStyle()](#getOtherStyle--) | إرجاع نمط نص آخر. |
| [getLayoutSlides()](#getLayoutSlides--) | إرجاع مجموعة الشرائح التخطيطية الفرعية لهذه الشريحة الرئيسة. |
| [getPreserve()](#getPreserve--) | تحديد ما إذا كانت الشريحة الرئيسة المقابلة تُحذف عندما تُحذف جميع الشرائح التي تتبع تلك الرئيسة. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | تحديد ما إذا كانت الشريحة الرئيسة المقابلة تُحذف عندما تُحذف جميع الشرائح التي تتبع تلك الرئيسة. |
| [getDependingSlides()](#getDependingSlides--) | إرجاع مصفوفة بجميع الشرائح التي تعتمد على هذه الشريحة الرئيسة. |
| [hasDependingSlides()](#hasDependingSlides--) | إرجاع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسة. |
| [getThemeManager()](#getThemeManager--) | إرجاع مدير السمة. |
| [getName()](#getName--) | إرجاع أو تعيين اسم الشريحة الرئيسة. |
| [setName(String value)](#setName-java.lang.String-) | إرجاع أو تعيين اسم الشريحة الرئيسة. |
| [getShowMasterShapes()](#getShowMasterShapes--) | تحديد ما إذا كانت الأشكال على الشريحة الرئيسة يجب أن تُعرض على الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | تحديد ما إذا كانت الأشكال على الشريحة الرئيسة يجب أن تُعرض على الشرائح أم لا. |
| [getDrawingGuides()](#getDrawingGuides--) | إرجاع مجموعة من أدلة الرسم للشريحة الرئيسة. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

إرجاع مدير HeaderFooter للشريحة الرئيسة. قراءة فقط [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**الإرجاع:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

إنشاء شريحة رئيسية جديدة بناءً على الحالية، مع تطبيق سمة خارجية عليها وتطبيق الشريحة الرئيسة التي تم إنشاؤها على جميع الشرائح التابعة.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى ملف السمة الخارجي (.thmx). |

**الإرجاع:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - شريحة رئيسية ذات سمة جديدة.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

إرجاع نمط نص العنوان. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

إرجاع نمط نص المتن. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

إرجاع نمط نص آخر. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

إرجاع مجموعة الشرائح التخطيطية الفرعية لهذه الشريحة الرئيسة. قراءة فقط [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

يمكنك الوصول إلى واجهة برمجة تطبيقات بديلة لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط باستخدام الخاصية ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**الإرجاع:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

تحديد ما إذا كانت الشريحة الرئيسة المقابلة تُحذف عندما تُحذف جميع الشرائح التي تتبع تلك الرئيسة. ملاحظة: Aspose.Slides لن يزيل أي شريحة رئيسة غير مستخدمة بمفرده، لإزالة الشرائح الرئيسية غير المستخدمة فعلاً استدعِ [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) القراءة/الكتابة  boolean .

**الإرجاع:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

تحديد ما إذا كانت الشريحة الرئيسة المقابلة تُحذف عندما تُحذف جميع الشرائح التي تتبع تلك الرئيسة. ملاحظة: Aspose.Slides لن يزيل أي شريحة رئيسة غير مستخدمة بمفرده، لإزالة الشرائح الرئيسية غير المستخدمة فعلاً استدعِ [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) القراءة/الكتابة  boolean .

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

إرجاع مصفوفة بجميع الشرائح التي تعتمد على هذه الشريحة الرئيسة.

**الإرجاع:**
com.aspose.slides.ISlide[] - مصفوفة من [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

إرجاع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسة. قراءة فقط  boolean .

**الإرجاع:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

إرجاع مدير السمة. قراءة فقط [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**الإرجاع:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

إرجاع أو تعيين اسم الشريحة الرئيسة. القراءة/الكتابة String.

**الإرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

إرجاع أو تعيين اسم الشريحة الرئيسة. القراءة/الكتابة String.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

تحديد ما إذا كانت الأشكال على الشريحة الرئيسة يجب أن تُعرض على الشرائح أم لا. بالنسبة للشريحة الرئيسة نفسها تُرجع هذه الخاصية دائمًا  false . القراءة/الكتابة  boolean .

**الإرجاع:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

تحديد ما إذا كانت الأشكال على الشريحة الرئيسة يجب أن تُعرض على الشرائح أم لا. بالنسبة للشريحة الرئيسة نفسها تُرجع هذه الخاصية دائمًا  false . القراءة/الكتابة  boolean .

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

إرجاع مجموعة من أدلة الرسم للشريحة الرئيسة. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
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


**الإرجاع:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)