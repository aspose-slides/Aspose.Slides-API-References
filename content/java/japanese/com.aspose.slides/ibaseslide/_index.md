---
title: IBaseSlide
second_title: Aspose.Slides for Java API リファレンス
description: すべてのスライドタイプに共通するデータを表します。
type: docs
url: /ja/com.aspose.slides/ibaseslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

すべてのスライドタイプに共通するデータを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShapes()](#getShapes--) | スライドのシェイプを取得します。 |
| [getControls()](#getControls--) | スライド上の ActiveX コントロールのコレクションを取得します。 |
| [getName()](#getName--) | スライドの名前を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | スライドの名前を取得または設定します。 |
| [getSlideId()](#getSlideId--) | スライドの ID を取得します。 |
| [getCustomData()](#getCustomData--) | スライドのカスタムデータを取得します。 |
| [getTimeline()](#getTimeline--) | アニメーションタイムラインオブジェクトを取得します。 |
| [getSlideShowTransition()](#getSlideShowTransition--) | 指定されたスライドがスライドショー中にどのように進行するかの情報を含む TransitionEx オブジェクトを取得します。 |
| [getBackground()](#getBackground--) | スライドの背景を取得します。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 含まれるハイパーリンクへの簡易アクセスを提供します。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | すべての許容可能なシェイプ内のすべての段落で、同じ書式のランを結合します。 |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 2 つの IBaseSlide インスタンスが等しいかどうかを判定します。 |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


スライドのシェイプを取得します。 読み取り専用 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**戻り値:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


スライド上の ActiveX コントロールのコレクションを取得します。 読み取り専用 [IControlCollection](../../com.aspose.slides/icontrolcollection)。

**戻り値:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


スライドの名前を取得または設定します。 読み書き可能 String。

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


スライドの名前を取得または設定します。 読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


スライドの ID を取得します。 読み取り専用 long。

**戻り値:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


スライドのカスタムデータを取得します。 読み取り専用 [ICustomData](../../com.aspose.slides/icustomdata)。

**戻り値:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


アニメーションタイムラインオブジェクトを取得します。 読み取り専用 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)。

**戻り値:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


指定されたスライドがスライドショー中にどのように進行するかの情報を含む TransitionEx オブジェクトを取得します。 読み取り専用 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition)。

**戻り値:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


スライドの背景を取得します。 読み取り専用 [IBackground](../../com.aspose.slides/ibackground)。

**戻り値:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


含まれるハイパーリンクへの簡易アクセスを提供します。 読み取り専用 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**戻り値:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 マスタースライド自体ではこのプロパティは常に false を返します。 読み書き可能 boolean。

**戻り値:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 マスタースライド自体ではこのプロパティは常に false を返します。 読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


指定された代替テキストを持つシェイプの最初の出現を検索します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| altText | java.lang.String | 代替テキスト。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx オブジェクトまたは null。
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


すべての許容可能なシェイプ内のすべての段落で、同じ書式のランを結合します。

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


2 つの IBaseSlide インスタンスが等しいかどうかを判定します。戻り値はスライドの構造と静的コンテンツに基づいて計算されます。すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、スライドは等しいとみなされます。比較は SlideId などの一意識別子や、日付プレースホルダーの現在の日付値などの動的コンテンツは考慮しません。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 現在の IBaseSlide と比較する対象の IBaseSlide。 |

**戻り値:**
boolean - **true**：指定された IBaseSlide が現在の IBaseSlide と等しい場合。 **false**：それ以外。