---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: ハイパーリンクの管理（追加、削除）を提供します。
type: docs
url: /ja/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

ハイパーリンクの管理（追加、削除）を提供します。
## メソッド

| メソッド | 説明 |
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

クリック時に外部ハイパーリンクを設定します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | java.lang.String | ハイパーリンク URL。 |

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

クリック時に内部ハイパーリンクを設定します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 対象のスライド。 |

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

クリック時にハイパーリンクを削除します。

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

マウスオーバー時に外部ハイパーリンクを設定します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | java.lang.String | ハイパーリンク URL。 |

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

マウスオーバー時に内部ハイパーリンクを設定します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 対象のスライド。 |

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

マウスオーバー時にハイパーリンクを削除します。

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

クリック時に Macro ハイパーリンクを設定します。

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


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| macroName | java.lang.String | マクロの名前 |

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)