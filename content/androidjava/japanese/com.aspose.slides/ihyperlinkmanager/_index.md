---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: ハイパーリンクの管理（追加、削除）を提供します。
type: docs
url: /ja/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

ハイパーリンクの管理（追加、削除）を提供します。

## メソッド

| Method | Description |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | クリック時に外部ハイパーリンクを設定します。 |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | クリック時に内部ハイパーリンクを設定します。 |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | クリック時にハイパーリンクを削除します。 |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | マウスオーバー時に外部ハイパーリンクを設定します。 |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | マウスオーバー時に内部ハイパーリンクを設定します。 |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | マウスオーバー時にハイパーリンクを削除します。 |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | クリック時にマクロハイパーリンクを設定します。 |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

クリック時に外部ハイパーリンクを設定します。

**パラメータ:**
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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 対象スライド。 |

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

**パラメータ:**
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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 対象スライド。 |

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

クリック時にマクロハイパーリンクを設定します。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| macroName | java.lang.String | マクロの名前 |

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)