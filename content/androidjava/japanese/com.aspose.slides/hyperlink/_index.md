---
title: Hyperlink
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: ハイパーリンクを表します。
type: docs
url: /ja/com.aspose.slides/hyperlink/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

ハイパーリンクを表します。

## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | ハイパーリンクのインスタンスを作成します。 |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | 特定のスライドを指すハイパーリンクのインスタンスを作成します。 |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | 別のハイパーリンクをソースとして使用し、二次プロパティを上書きしたハイパーリンクのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | 特別な「何もしない」ハイパーリンクを返します。 |
| [getMedia()](#getMedia--) | 特別な「メディアファイルを再生」ハイパーリンクを返します。 |
| [getNextSlide()](#getNextSlide--) | 次のスライドへのハイパーリンクを返します。 |
| [getPreviousSlide()](#getPreviousSlide--) | 前のスライドへのハイパーリンクを返します。 |
| [getFirstSlide()](#getFirstSlide--) | プレゼンテーションの最初のスライドへのハイパーリンクを返します。 |
| [getLastSlide()](#getLastSlide--) | プレゼンテーションの最後のスライドへのハイパーリンクを返します。 |
| [getLastVievedSlide()](#getLastVievedSlide--) | 最後に表示されたスライドへのハイパーリンクを返します。 |
| [getEndShow()](#getEndShow--) | ショーを終了するハイパーリンクを返します。 |
| [getActionType()](#getActionType--) | Hyperlink のアクションの種類を返します。 |
| [getExternalUrl()](#getExternalUrl--) | 外部 URL を指定します。 |
| [getTargetSlide()](#getTargetSlide--) | Hyperlink が特定のスライドを対象としている場合、そのスライドを返します。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 実際のコンテンツに関係なく、この部分に設定されたハイパーリンクを表します。 |
| [getTargetFrame()](#getTargetFrame--) | 親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内のフレームを返します。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内のフレームを返します。 |
| [getTooltip()](#getTooltip--) | 親ハイパーリンクに関連付けられた UI に表示される可能性のある文字列を返します。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 親ハイパーリンクに関連付けられた UI に表示される可能性のある文字列を返します。 |
| [getHistory()](#getHistory--) | 親ハイパーリンクの対象が呼び出されたときに、閲覧済みハイパーリンクのリストに追加されるかどうかを決定します。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 親ハイパーリンクの対象が呼び出されたときに、閲覧済みハイパーリンクのリストに追加されるかどうかを決定します。 |
| [getHighlightClick()](#getHighlightClick--) | クリック時にハイパーリンクをハイライトするかどうかを決定します。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | クリック時にハイパーリンクをハイライトするかどうかを決定します。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | クリック時にサウンドを停止するかどうかを決定します。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | クリック時にサウンドを停止するかどうかを決定します。 |
| [getSound()](#getSound--) | ハイパーリンクの再生中サウンドを表します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | ハイパーリンクの再生中サウンドを表します。 |
| [getColorSource()](#getColorSource--) | ハイパーリンクの色のソース（スタイルまたは部分フォーマット）を表します。 |
| [setColorSource(int value)](#setColorSource-int-) | ハイパーリンクの色のソース（スタイルまたは部分フォーマット）を表します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 2 つの Hyperlink インスタンスが等しいかどうかを決定します。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 2 つの Hyperlink インスタンスが等しいかどうかを決定します。 |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 2 つのハイパーリンクの等価性をテストします。 |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 2 つのハイパーリンクの非等価性をテストします。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能し、ハッシュテーブルなどのデータ構造で使用できます。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

ハイパーリンクのインスタンスを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| url | java.lang.String | ハイパーリンク URL。 |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

特定のスライドを指すハイパーリンクのインスタンスを作成します。注: 作成されたハイパーリンクは同じプレゼンテーション内のオブジェクトに割り当てる必要があります。そうでない場合、リンクは NoAction として保存されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 対象スライド。 |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

別のハイパーリンクをソースとして使用し、二次プロパティを上書きしたハイパーリンクのインスタンスを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | ソースハイパーリンク |
| targetFrame | java.lang.String | 対象フレーム |
| tooltip | java.lang.String | ツールチップテキスト |
| history | boolean | 親ハイパーリンクの対象が呼び出されたときに、閲覧済みハイパーリンクのリストに追加されるかどうかを決定します。 |
| stopSoundsOnClick | boolean | クリック時にサウンドを停止するかどうかを決定します。 |
| highlightClick | boolean | クリック時にハイパーリンクをハイライトするかどうかを決定します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

特別な「何もしない」ハイパーリンクを返します。読み取り専用 [Hyperlink](../../com.aspose.slides/hyperlink)。

**戻り値:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

特別な「メディアファイルを再生」ハイパーリンクを返します。AudioFrame と VideoFrame で使用されます。読み取り専用 [Hyperlink](../../com.aspose.slides/hyperlink)。

**戻り値:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

次のスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](../../com.aspose.slides/hyperlink)。

**戻り値:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

前のスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](../../com.aspose.slides/hyperlink)。

**戻り値:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

プレゼンテーションの最初のスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](../../com.aspose.slides/hyperlink)。

**戻り値:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

プレゼンテーションの最後のスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](../../com.aspose.slides/hyperlink)。

**戻り値:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

最後に表示されたスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](../../com.aspose.slides/hyperlink)。

**戻り値:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

ショーを終了するハイパーリンクを返します。読み取り専用 [Hyperlink](../../com.aspose.slides/hyperlink)。

**戻り値:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Hyperlink のアクションの種類を返します。読み取り専用 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

**戻り値:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

外部 URL を指定します。読み取り専用 String。

**戻り値:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Hyperlink が特定のスライドを対象としている場合、そのスライドを返します。読み取り専用 [ISlide](../../com.aspose.slides/islide)。

**戻り値:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

実際のコンテンツに関係なく、この部分に設定されたハイパーリンクを表します。

--------------------

PowerPoint はリンクとそれに対応するテキストが部分内にある場合に特別な動作をします。リンクのテキストとして有効な URL 形式の文字列を作成でき、実際のリンク先アドレスとは異なるものにできます。この場合、編集ウィンドウでリンクを表示すると、テキスト部分に合わせて変更されます。このプロパティはハイパーリンクの元の値を表します。

**戻り値:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内のフレームを返します。読み書き可能 String。

**戻り値:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内のフレームを設定します。読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

親ハイパーリンクに関連付けられた UI に表示される可能性のある文字列を返します。読み書き可能 String。

**戻り値:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

親ハイパーリンクに関連付けられた UI に表示される可能性のある文字列を設定します。読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

親ハイパーリンクの対象が呼び出されたときに、閲覧済みハイパーリンクのリストに追加されるかどうかを決定します。読み書き可能 boolean。

**戻り値:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

親ハイパーリンクの対象が呼び出されたときに、閲覧済みハイパーリンクのリストに追加されるかどうかを決定します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

クリック時にハイパーリンクをハイライトするかどうかを決定します。読み書き可能 boolean。

**戻り値:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

クリック時にハイパーリンクをハイライトするかどうかを設定します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

クリック時にサウンドを停止するかどうかを決定します。読み書き可能 boolean。

**戻り値:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

クリック時にサウンドを停止するかどうかを設定します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

ハイパーリンクの再生中サウンドを表します。読み書き可能 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 最初のシェイプのハイパーリンクを取得します
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // ハイパーリンクのサウンドをバイト配列として抽出します
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

ハイパーリンクの再生中サウンドを設定します。読み書き可能 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 最初のシェイプのハイパーリンクを取得します
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // ハイパーリンクのサウンドをバイト配列として抽出します
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

ハイパーリンクの色のソース（スタイルまたは部分フォーマット）を表します。読み書き可能 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**戻り値:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

ハイパーリンクの色のソース（スタイルまたは部分フォーマット）を設定します。読み書き可能 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

2 つの Hyperlink インスタンスが等しいかどうかを決定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の Hyperlink。 |

**戻り値:**
boolean - 指定された Hyperlink が現在の Hyperlink と等しい場合は **true**、それ以外は **false**。

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

2 つの Hyperlink インスタンスが等しいかどうかを決定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 比較対象の Hyperlink。 |

**戻り値:**
boolean - 指定された Hyperlink が現在の Hyperlink と等しい場合は **true**、それ以外は **false**。

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

2 つのハイパーリンクの等価性をテストします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | テスト対象の最初のハイパーリンク。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | テスト対象の第二のハイパーリンク。 |

**戻り値:**
boolean - ハイパーリンクが等しい場合は **true**。

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

2 つのハイパーリンクの非等価性をテストします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | テスト対象の最初のハイパーリンク。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | テスト対象の第二のハイパーリンク。 |

**戻り値:**
boolean - ハイパーリンクが等しい場合は **false**。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能し、ハッシュテーブルなどのデータ構造で使用できます。

**戻り値:**
int - URL のハッシュコード。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject