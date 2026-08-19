---
title: HyperlinkManager
second_title: مرجع API Aspose.Slides برای جاوا
description: مدیریت افزودن و حذف پیوندهای ابرمتن را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/hyperlinkmanager/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject  
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

مدیریت پیوندهای ابرمتن (افزودن، حذف) را فراهم می‌کند.

## متدها

| متد | توضیح |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | تنظیم پیوند ابرمتن خارجی هنگام کلیک. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | تنظیم پیوند ابرمتن داخلی هنگام کلیک. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | حذف پیوند ابرمتن هنگام کلیک. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | تنظیم پیوند ابرمتن خارجی هنگام نشانگر ماوس. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | تنظیم پیوند ابرمتن داخلی هنگام نشانگر ماوس. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | حذف پیوند ابرمتن هنگام نشانگر ماوس. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | تنظیم پیوند ابرمتنی ماکرو هنگام کلیک. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

تنظیم پیوند ابرمتن خارجی هنگام کلیک.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // یک شی Presentation می‌سازد که نمایانگر یک فایل PPTX است
>  Presentation pres = new Presentation();
>  try {
>      // اولین اسلاید را در ارائه دریافت می‌کند
>      ISlide slide = pres.getSlides().get_Item(0);
>      // یک شی AutoShape با نوع Rectangle اضافه می‌کند
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // شکل را به AutoShape تبدیل می‌کند
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // به خصوصیت ITextFrame مرتبط با AutoShape دسترسی پیدا می‌کند
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // متنی به فریم اضافه می‌کند
>      portion.setText("Aspose.Slides");
>      // پیوند ابرمتن را برای متن قسمت تنظیم می‌کند
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // ارائه PPTX را ذخیره می‌کند
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL پیوند ابرمتن. |

**بازگشت:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

تنظیم پیوند ابرمتن داخلی هنگام کلیک.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

**بازگشت:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

حذف پیوند ابرمتن هنگام کلیک.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

تنظیم پیوند ابرمتن خارجی هنگام نشانگر ماوس.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL پیوند ابرمتن. |

**بازگشت:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

تنظیم پیوند ابرمتن داخلی هنگام نشانگر ماوس.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

**بازگشت:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

حذف پیوند ابرمتن هنگام نشانگر ماوس.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

تنظیم پیوند ابرمتن ماکرو هنگام کلیک.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| macroName | java.lang.String | نام ماکرو |

**بازگشت:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

بازگرداندن شیء Parent_Immediate. فقط-خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject