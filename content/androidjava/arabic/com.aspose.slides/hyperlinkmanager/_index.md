---
title: HyperlinkManager
second_title: Aspose.Slides لنظام Android عبر مرجع API للجافا
description: توفير إدارة الروابط التشعبية، الإضافة والإزالة.
type: docs
url: /ar/com.aspose.slides/hyperlinkmanager/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

توفير إدارة الروابط التشعبية (الإضافة والإزالة).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | تعيين ارتباط تشعبي خارجي عند النقر. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | تعيين ارتباط تشعبي داخلي عند النقر. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | إزالة الارتباط التشعبي عند النقر. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | تعيين ارتباط تشعبي خارجي عند مرور الفأرة. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | تعيين ارتباط تشعبي داخلي عند مرور الفأرة. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | إزالة الارتباط التشعبي عند مرور الفأرة. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | تعيين ارتباط تشعبي للماكرو عند النقر. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


تعيين ارتباط تشعبي خارجي عند النقر.

--------------------

> ```
> الكود العيني التالي يوضح كيفية إضافة مربع نص مع ارتباط تشعبي.
>  
>  // إنشاء كائن من فئة Presentation يمثل ملف PPTX
>  Presentation pres = new Presentation();
>  try {
>      // الحصول على الشريحة الأولى في العرض التقديمي
>      ISlide slide = pres.getSlides().get_Item(0);
>      // إضافة كائن AutoShape مع تحديد النوع كمستطيل
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // تحويل الشكل إلى AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // الوصول إلى الخاصية ITextFrame المرتبطة بـ AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // إضافة بعض النص إلى الإطار
>      portion.setText("Aspose.Slides");
>      // تعيين الارتباط التشعبي لنص الجزء
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // حفظ عرض PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL للارتباط التشعبي. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


تعيين ارتباط تشعبي داخلي عند النقر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة الهدف. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - ارتباط تشعبي.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


إزالة الارتباط التشعبي عند النقر.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


تعيين ارتباط تشعبي خارجي عند مرور الفأرة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL للارتباط التشعبي. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - ارتباط تشعبي.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


تعيين ارتباط تشعبي داخلي عند مرور الفأرة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة الهدف. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - ارتباط تشعبي.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


إزالة الارتباط التشعبي عند مرور الفأرة.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


تعيين ارتباط تشعبي للماكرو عند النقر.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| macroName | java.lang.String | اسم الماكرو |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - كائن ارتباط تشعبي [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


إرجاع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject