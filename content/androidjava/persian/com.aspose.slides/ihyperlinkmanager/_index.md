---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: مدیریت پیوندهای ابرمتنی (افزودن، حذف).
type: docs
url: /fa/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

مدیریت پیوندهای ابرمتنی (افزودن، حذف) را فراهم می‌کند.
## متدها

| Method | Description |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | تنظیم پیوند ابرمتنی خارجی در زمان کلیک. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | تنظیم پیوند ابرمتنی داخلی در زمان کلیک. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | حذف پیوند ابرمتنی در زمان کلیک. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | تنظیم پیوند ابرمتنی خارجی هنگام رفتن موس. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | تنظیم پیوند ابرمتنی داخلی هنگام رفتن موس. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | حذف پیوند ابرمتنی هنگام رفتن موس. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | تنظیم پیوند ابرمتنی ماکرو در زمان کلیک. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

تنظیم پیوند ابرمتنی خارجی در زمان کلیک.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | آدرس URL پیوند ابرمتنی. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - شی Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

تنظیم پیند ابرمتنی داخلی در زمان کلیک.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

حذف پیوند ابرمتنی در زمان کلیک.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

تنظیم پیوند ابرمتنی خارجی هنگام رفتن موس.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | آدرس URL پیوند ابرمتنی. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

تنظیم پیوند ابرمتنی داخلی هنگام رفتن موس.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

حذف پیوند ابرمتنی هنگام رفتن موس.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

تنظیم پیوند ابرمتنی ماکرو در زمان کلیک.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - شی Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)