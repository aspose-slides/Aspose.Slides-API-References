---
title: IHyperlinkManager
second_title: Aspose.Slides for Java مستندات API
description: مدیریت پیوندهای هایپرلینک (افزودن، حذف) را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

مدیریت پیوندهای هایپرلینک (افزودن، حذف).

## متدها

| متد | توضیح |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | تنظیم هایپرلینک خارجی هنگام کلیک. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | تنظیم هایپرلینک داخلی هنگام کلیک. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | حذف هایپرلینک هنگام کلیک. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | تنظیم هایپرلینک خارجی هنگام قرارگیری ماوس. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | تنظیم هایپرلینک داخلی هنگام قرارگیری ماوس. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | حذف هایپرلینک هنگام قرارگیری ماوس. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | تنظیم هایپرلینک ماکرو هنگام کلیک. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

تنظیم هایپرلینک خارجی هنگام کلیک.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL هایپرلینک. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - شیء هایپرلینک [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

تنظیم هایپرلینک داخلی هنگام کلیک.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - هایپرلینک.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

حذف هایپرلینک هنگام کلیک.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

تنظیم هایپرلینک خارجی هنگام قرارگیری ماوس.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL هایپرلینک. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - هایپرلینک.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

تنظیم هایپرلینک داخلی هنگام قرارگیری ماوس.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - هایپرلینک.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

حذف هایپرلینک هنگام قرارگیری ماوس.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

تنظیم هایپرلینک ماکرو هنگام کلیک.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - شیء هایپرلینک [IHyperlink](../../com.aspose.slides/ihyperlink)