---
title: BaseSlide
second_title: Aspose.Slides for Java API リファレンス
description: すべてのスライドタイプに共通のデータを表します。
type: docs
url: /ja/com.aspose.slides/baseslide/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

すべてのスライドタイプに共通のデータを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShapes()](#getShapes--) | スライドのシェイプを返します。 |
| [getControls()](#getControls--) | スライド上の ActiveX コントロールのコレクションを返します。 |
| [getName()](#getName--) | スライドの名前を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | スライドの名前を取得または設定します。 |
| [getSlideId()](#getSlideId--) | スライドの ID を返します。 |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 2 つの IBaseSlide インスタンスが等しいかどうかを判断します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。 |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。 |
| [createThemeEffective()](#createThemeEffective--) | このスライドの有効なテーマを返します。 |
| [getCustomData()](#getCustomData--) | スライドのカスタムデータを返します。 |
| [getTimeline()](#getTimeline--) | アニメーションタイムラインオブジェクトを返します。 |
| [getSlideShowTransition()](#getSlideShowTransition--) | スライドショー中に指定されたスライドがどのように進むかに関する情報を含む Transition オブジェクトを返します。 |
| [getBackground()](#getBackground--) | スライドの背景を返します。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 含まれるハイパーリンクへの簡単なアクセスを提供します。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | IPresentation インターフェイスを返します。 |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

スライドのシェイプを返します。読み取り専用 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**返り値:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

スライド上の ActiveX コントロールのコレクションを返します。読み取り専用 [IControlCollection](../../com.aspose.slides/icontrolcollection)。

**返り値:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public String getName()
```

スライドの名前を取得または設定します。読み書き String。

**返り値:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

スライドの名前を取得または設定します。読み書き String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

スライドの ID を返します。読み取り専用 long。

**返り値:**
long

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

2 つの IBaseSlide インスタンスが等しいかどうかを判断します。戻り値はスライドの構造と静的コンテンツに基づいて計算されます。すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、2 つのスライドは等しいとみなされます。比較では SlideId などの一意の識別子や、日付プレースホルダーの現在の日付値などの動的コンテンツは考慮されません。

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 現在の IBaseSlide と比較する対象の IBaseSlide。 |

**返り値:**
boolean -  **true**  if the specified IBaseSlide is equal to the current IBaseSlide; otherwise,  **false** .

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

このスライドの有効なテーマを返します。

**返り値:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

スライドのカスタムデータを返します。読み取り専用 [ICustomData](../../com.aspose.slides/icustomdata)。

**返り値:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

アニメーションタイムラインオブジェクトを返します。読み取り専用 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)。

**返り値:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)

### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

スライドショー中に指定されたスライドがどのように進むかに関する情報を含む Transition オブジェクトを返します。読み取り専用 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition)。

**返り値:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

スライドの背景を返します。読み取り専用 [IBackground](../../com.aspose.slides/ibackground)。

**返り値:**
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

含まれるハイパーリンクへの簡単なアクセスを提供します。読み取り専用 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返り値:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。マスタースライド自体に対してはこのプロパティは常に false を返します。読み書き boolean。

**返り値:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。マスタースライド自体に対してはこのプロパティは常に false を返します。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

指定された代替テキストを持つシェイプの最初の出現を検索します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| altText | java.lang.String | 代替テキスト。 |

**返り値:**
[IShape](../../com.aspose.slides/ishape) - Shape object or null.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**返り値:**
com.aspose.slides.IDOMObject

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

IPresentation インターフェイスを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**返り値:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ベーススライドを返します。読み取り専用 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)