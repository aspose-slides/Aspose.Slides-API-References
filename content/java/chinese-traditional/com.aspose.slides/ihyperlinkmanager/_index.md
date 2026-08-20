---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: Provide hyperlinks management adding removing.
type: docs
url: /zh-hant/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

提供超連結管理（新增、移除）。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Set external hyperlink on click. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Sets internal hyperlink on click. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Removes hyperlink on click. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Sets external hyperlink mouse over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Sets internal hyperlink mouse over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Removes hyperlink mouse over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Set Macro hyperlink on a click. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

在點擊時設定外部超連結。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 超連結 URL。 |

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 物件 [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

在點擊時設定內部超連結。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink。
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

移除點擊時的超連結。

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

在滑鼠懸停時設定外部超連結。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 超連結 URL。 |

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink。

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

在滑鼠懸停時設定內部超連結。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink。

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

移除滑鼠懸停時的超連結。

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

在點擊時設定巨集超連結。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| macroName | java.lang.String | 巨集名稱 |

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 物件 [IHyperlink](../../com.aspose.slides/ihyperlink)