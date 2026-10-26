---
title: PortionFormat
second_title: Aspose.Slides for Android の Java API リファレンス
description: このクラスはテキスト部分の書式設定プロパティを含みます。
type: docs
url: /ja/com.aspose.slides/portionformat/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**実装されている全インターフェイス:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

このクラスはテキスト部分の書式設定プロパティを含みます。[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)とは異なり、このクラスのすべてのプロパティは書き込み可能です。

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //プレゼンテーションファイルを表すプレゼンテーションオブジェクトをインスタンス化します
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides はこれらの特別な識別子を使用します（PowerPoint で使用されるものと同様です）:
>      // +mn-lt - 本文フォント ラテン文字 (マイナー ラテンフォント)
>      // +mj-lt - 見出しフォント ラテン文字 (メジャー ラテンフォント)
>      // +mn-ea - 本文フォント 東アジア文字 (マイナー 東アジアフォント)
>      // +mj-ea - 本文フォント 東アジア文字 (マイナー 東アジアフォント)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

このクラスは、特定の部分に定義されたテキスト部分の書式設定プロパティを取得および操作するために使用されます。これは、値を取得する際に継承が適用されないことを意味し、ほとんどの場合「未定義」の値が返されます。

継承を含む有効な書式設定パラメータ値を取得するには、[getEffective](../../com.aspose.slides/portionformat\#getEffective)メソッドを使用する必要があり、このメソッドは[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)インスタンスを返します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | [PortionFormat](../../com.aspose.slides/portionformat) クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | ブックマーク識別子を取得または設定します。 |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | ブックマーク識別子を取得または設定します。 |
| [getSmartTagClean()](#getSmartTagClean--) | スマートタグをクリアすべきかどうかを判定します。 |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | スマートタグをクリアすべきかどうかを判定します。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | マウスクリック用に定義されたハイパーリンクを取得または設定します。 |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | マウスクリック用に定義されたハイパーリンクを取得または設定します。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。 |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。 |
| [getHyperlinkManager()](#getHyperlinkManager--) | ハイパーリンクマネージャー。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な部分書式設定データを取得します。 |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

[PortionFormat](../../com.aspose.slides/portionformat) クラスの新しいインスタンスを初期化します。

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

ブックマーク識別子を取得または設定します。読み書き可能な String。

**戻り値:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

ブックマーク識別子を取得または設定します。読み書き可能な String。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

スマートタグをクリアすべきかどうかを判定します。継承は適用されません。読み書き可能な boolean 。

**戻り値:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

スマートタグをクリアすべきかどうかを判定します。継承は適用されません。読み書き可能な boolean 。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き可能な [IHyperlink](../../com.aspose.slides/ihyperlink)。

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き可能な [IHyperlink](../../com.aspose.slides/ihyperlink)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き可能な [IHyperlink](../../com.aspose.slides/ihyperlink)。

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き可能な [IHyperlink](../../com.aspose.slides/ihyperlink)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

ハイパーリンクマネージャー。読み取り専用 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)。

**戻り値:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

継承が適用された有効な部分書式設定データを取得します。

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).