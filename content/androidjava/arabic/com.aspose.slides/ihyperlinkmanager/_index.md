---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: توفير إدارة الارتباطات التشعبية (الإضافة والإزالة).
type: docs
url: /ar/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

توفير إدارة الارتباطات التشعبية (الإضافة والإزالة).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | تعيين ارتباط تشعبي خارجي عند النقر. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | تعيين ارتباط تشعبي داخلي عند النقر. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | إزالة الارتباط التشعبي عند النقر. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | تعيين ارتباط تشعبي خارجي عند حركة الفأرة. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | تعيين ارتباط تشعبي داخلي عند حركة الفأرة. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | إزالة الارتباط التشعبي عند حركة الفأرة. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | تعيين ارتباط تشعبي ماكرو عند النقر. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

تعيين ارتباط تشعبي خارجي عند النقر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL للارتباط التشعبي. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - كائن Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

تعيين ارتباط تشعبي داخلي عند النقر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المستهدفة. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

إزالة الارتباط التشعبي عند النقر.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

تعيين ارتباط تشعبي خارجي عند حركة الفأرة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL للارتباط التشعبي. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - كائن Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

تعيين ارتباط تشعبي داخلي عند حركة الفأرة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المستهدفة. |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - كائن Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

إزالة الارتباط التشعبي عند حركة الفأرة.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

تعيين ارتباط تشعبي ماكرو عند النقر.

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| macroName | java.lang.String | اسم الماكرو |

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - كائن Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)