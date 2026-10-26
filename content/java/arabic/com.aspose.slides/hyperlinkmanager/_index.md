---
title: HyperlinkManager
second_title: مرجع API لـ Aspose.Slides لجافا
description: توفر إدارة الروابط التشعبية بإضافة وإزالة.
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

Provide hyperlinks management (adding, removing).
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | ضبط الارتباط التشعبي الخارجي عند النقر. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | يضبط الارتباط التشعبي الداخلي عند النقر. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | يزيل الارتباط التشعبي عند النقر. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | يضبط الارتباط التشعبي الخارجي عند مرور الفأرة. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | يضبط الارتباط التشعبي الداخلي عند مرور الفأرة. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | يزيل الارتباط التشعبي عند مرور الفأرة. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | ضبط الارتباط التشعبي للماكرو عند النقر. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

ضبط الارتباط التشعبي الخارجي عند النقر.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // ينشئ كائن من فئة Presentation يمثل ملف PPTX
>  Presentation pres = new Presentation();
>  try {
>      // يحصل على الشريحة الأولى في العرض التقديمي
>      ISlide slide = pres.getSlides().get_Item(0);
>      // يضيف كائن AutoShape مع تعيين النوع كـ Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // يحول الشكل إلى AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // يصل إلى خاصية ITextFrame المرتبطة بـ AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // يضيف بعض النص إلى الإطار
>      portion.setText("Aspose.Slides");
>      // يحدد الارتباط التشعبي لنص الجزء
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // يحفظ عرض PPTX
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

يضبط الارتباط التشعبي الداخلي عند النقر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المستهدفة. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - الارتباط التشعبي.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

يزيل الارتباط التشعبي عند النقر.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

يضبط الارتباط التشعبي الخارجي عند مرور الفأرة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL للارتباط التشعبي. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - الارتباط التشعبي.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

يضبط الارتباط التشعبي الداخلي عند مرور الفأرة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المستهدفة. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - الارتباط التشعبي.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

يزيل الارتباط التشعبي عند مرور الفأرة.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

ضبط الارتباط التشعبي للماكرو عند النقر.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - كائن الارتباط التشعبي [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject