---
title: HyperlinkManager
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ハイパーリンクの管理（追加および削除）を提供します。
type: docs
url: /ja/com.aspose.slides/hyperlinkmanager/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

ハイパーリンクの管理（追加、削除）を提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | クリック時に外部ハイパーリンクを設定します。 |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | クリック時に内部ハイパーリンクを設定します。 |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | クリック時にハイパーリンクを削除します。 |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | マウスオーバー時に外部ハイパーリンクを設定します。 |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | マウスオーバー時に内部ハイパーリンクを設定します。 |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | マウスオーバー時にハイパーリンクを削除します。 |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | クリック時にマクロハイパーリンクを設定します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

クリック時に外部ハイパーリンクを設定します。

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // PPTX を表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try {
>      // プレゼンテーションの最初のスライドを取得します
>      ISlide slide = pres.getSlides().get_Item(0);
>      // タイプを Rectangle に設定した AutoShape オブジェクトを追加します
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // シェイプを AutoShape にキャストします
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Accesses the ITextFrame property associated with the AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // フレームにテキストを追加します
>      portion.setText("Aspose.Slides");
>      // 部分テキストのハイパーリンクを設定します
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // PPTX プレゼンテーションを保存します
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | java.lang.String | ハイパーリンク URL。 |

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

クリック時に内部ハイパーリンクを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | ターゲット スライド。 |

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

クリック時にハイパーリンクを削除します。

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
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
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

マウスオーバー時に内部ハイパーリンクを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | ターゲット スライド。 |

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

マウスオーバー時にハイパーリンクを削除します。

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
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

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject