---
title: HyperlinkManager
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: مدیریت پیوندهای ابرمتنی را برای افزودن و حذف فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/hyperlinkmanager/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

مدیریت پیوندهای ابرمتنی (افزودن، حذف) را فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | تنظیم پیوند ابرمتنی خارجی هنگام کلیک. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | تنظیم پیوند ابرمتنی داخلی هنگام کلیک. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | حذف پیوند ابرمتنی هنگام کلیک. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | تنظیم پیوند ابرمتنی خارجی هنگام قرار گرفتن موس. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | تنظیم پیوند ابرمتنی داخلی هنگام قرار گرفتن موس. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | حذف پیوند ابرمتنی هنگام قرار گرفتن موس. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | تنظیم پیوند ماکرو هنگام کلیک. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


تنظیم پیوند ابرمتنی خارجی هنگام کلیک.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // یک شی از کلاس Presentation ایجاد می‌کند که نمایان‌گر یک فایل PPTX است
>  Presentation pres = new Presentation();
>  try {
>      // اسلاید اول ارائه را دریافت می‌کند
>      ISlide slide = pres.getSlides().get_Item(0);
>      // یک شی AutoShape با نوع مستطیل اضافه می‌کند
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // شکل را به AutoShape تبدیل می‌کند
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Accesses the ITextFrame property associated with the AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // متنی به فریم اضافه می‌کند
>      portion.setText("Aspose.Slides");
>      // پیوند ابرمتنی را برای متن بخش تنظیم می‌کند
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // ارائه PPTX را ذخیره می‌کند
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL پیوند ابرمتنی. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


تنظیم پیوند ابرمتنی داخلی هنگام کلیک.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


حذف پیوند ابرمتنی هنگام کلیک.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


تنظیم پیوند ابرمتنی خارجی هنگام قرار گرفتن موس.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL پیوند ابرمتنی. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


تنظیم پیوند ابرمتنی داخلی هنگام قرار گرفتن موس.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


حذف پیوند ابرمتنی هنگام قرار گرفتن موس.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


تنظیم پیوند ماکرو هنگام کلیک.

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
| Parameter | Type | Description |
| --- | --- | --- |
| macroName | java.lang.String | نام ماکرو |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


باز می‌گرداند Parent_Immediate object. فقط-خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject