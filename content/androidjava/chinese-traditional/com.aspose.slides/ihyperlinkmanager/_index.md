---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API 參考文件
description: 提供超連結管理（新增、移除）。
type: docs
url: /zh-hant/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

提供超連結管理（新增、移除）。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | 設定點擊時的外部超連結。 |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | 設定點擊時的內部超連結。 |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | 移除點擊的超連結。 |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | 設定滑鼠懸停時的外部超連結。 |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | 設定滑鼠懸停時的內部超連結。 |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | 移除滑鼠懸停時的超連結。 |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | 設定點擊時的 Macro 超連結。 |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

設定點擊時的外部超連結。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 超連結 URL。 |

**傳回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 物件 [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

設定點擊時的內部超連結。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

**傳回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

移除點擊時的超連結。
### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

設定滑鼠懸停時的外部超連結。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 超連結 URL。 |

**傳回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

設定滑鼠懸停時的內部超連結。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

**傳回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

移除滑鼠懸停時的超連結。
### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

設定點擊時的 Macro 超連結。

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
| macroName | java.lang.String | Macro 的名稱 |

**傳回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 物件 [IHyperlink](../../com.aspose.slides/ihyperlink)