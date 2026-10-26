---
title: Hyperlink
second_title: Aspose.Slides for Java API リファレンス
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
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | 別のハイパーリンクをソースとして使用し、セカンダリ プロパティを上書きしたハイパーリンクのインスタンスを作成します。 |
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
| [getActionType()](#getActionType--) | ハイパーリンクのアクションのタイプを返します。 |
| [getExternalUrl()](#getExternalUrl--) | 外部 URL を指定します。 |
| [getTargetSlide()](#getTargetSlide--) | ハイパーリンクが特定のスライドを対象とする場合、そのスライドを返します。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 実際の内容に関係なくこの部分に設定されたハイパーリンクを表します。 |
| [getTargetFrame()](#getTargetFrame--) | 存在する場合、親ハイパーリンクの対象のフレームを親 HTML フレームセット内で返します。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 存在する場合、親ハイパーリンクの対象のフレームを親 HTML フレームセット内で返します。 |
| [getTooltip()](#getTooltip--) | ユーザーインターフェイスに表示される可能性のある文字列（親ハイパーリンクに関連付けられた）を返します。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | ユーザーインターフェイスに表示される可能性のある文字列（親ハイパーリンクに関連付けられた）を返します。 |
| [getHistory()](#getHistory--) | 呼び出されたときに、親ハイパーリンクの対象を閲覧済みハイパーリンクのリストに追加するかどうかを決定します。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 呼び出されたときに、親ハイパーリンクの対象を閲覧済みハイパーリンクのリストに追加するかどうかを決定します。 |
| [getHighlightClick()](#getHighlightClick--) | クリック時にハイパーリンクをハイライト表示するかどうかを決定します。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | クリック時にハイパーリンクをハイライト表示するかどうかを決定します。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | ハイパーリンクのクリック時にサウンドを停止するかどうかを決定します。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | ハイパーリンクのクリック時にサウンドを停止するかどうかを決定します。 |
| [getSound()](#getSound--) | ハイパーリンクの再生サウンドを表します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | ハイパーリンクの再生サウンドを表します。 |
| [getColorSource()](#getColorSource--) | ハイパーリンクの色のソースを表します（スタイルまたは部分フォーマット）。 |
| [setColorSource(int value)](#setColorSource-int-) | ハイパーリンクの色のソースを表します（スタイルまたは部分フォーマット）。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 2 つの Hyperlink インスタンスが等しいかどうかを決定します。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 2 つの Hyperlink インスタンスが等しいかどうかを決定します。 |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 2 つのハイパーリンクが等しいかテストします。 |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 2 つのハイパーリンクが等しくないかテストします。 |
| [hashCode()](#hashCode--) | ハッシュテーブルなどのハッシュアルゴリズムやデータ構造で使用できる、特定の型に対するハッシュ関数として機能します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

ハイパーリンクのインスタンスを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| url | java.lang.String | ハイパーリンクの URL。 |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

特定のスライドを指すハイパーリンクのインスタンスを作成します。注意: 作成されたハイパーリンクは同じプレゼンテーションのオブジェクトに割り当てる必要があります。そうでない場合、リンクは NoAction として保存されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 対象スライド。 |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

別のハイパーリンクをソースとして使用し、セカンダリ プロパティを上書きしたハイパーリンクのインスタンスを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | ソースハイパーリンク |
| targetFrame | java.lang.String | 対象フレーム |
| tooltip | java.lang.String | ツールチップテキスト |
| history | boolean | 呼び出されたときに、親ハイパーリンクの対象を閲覧済みハイパーリンクのリストに追加するかどうかを決定します。 |
| stopSoundsOnClick | boolean | ハイパーリンクのクリック時にサウンドを停止するかどうかを決定します。 |
| highlightClick | boolean | クリック時にハイパーリンクをハイライト表示するかどうかを決定します。 |

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

ハイパーリンクのアクションのタイプを返します。読み取り専用 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

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

ハイパーリンクが特定のスライドを対象とする場合、そのスライドを返します。読み取り専用 [ISlide](../../com.aspose.slides/islide)。

**戻り値:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

実際の内容に関係なくこの部分に設定されたハイパーリンクを表します。

--------------------

PowerPoint はリンクとそれに対応する部分のテキストに対して特別な動作をします。リンクの実際のアドレスとは異なる有効な URL の形式でハイパーリンクのテキストを作成できます。この場合、編集ウィンドウでリンクを表示すると、テキスト部分に合わせて変更されます。このプロパティはハイパーリンクの元の値を表します。

**戻り値:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

存在する場合、親ハイパーリンクの対象のフレームを親 HTML フレームセット内で返します。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

存在する場合、親ハイパーリンクの対象のフレームを親 HTML フレームセット内で返します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

ユーザーインターフェイスに表示される可能性のある文字列（親ハイパーリンクに関連付けられた）を返します。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

ユーザーインターフェイスに表示される可能性のある文字列（親ハイパーリンクに関連付けられた）を返します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

呼び出されたときに、親ハイパーリンクの対象を閲覧済みハイパーリンクのリストに追加するかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

呼び出されたときに、親ハイパーリンクの対象を閲覧済みハイパーリンクのリストに追加するかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

クリック時にハイパーリンクをハイライト表示するかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

クリック時にハイパーリンクをハイライト表示するかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

ハイパーリンクのクリック時にサウンドを停止するかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

ハイパーリンクのクリック時にサウンドを停止するかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

ハイパーリンクの再生サウンドを表します。読み取り/書き込み [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 最初の形状のハイパーリンクを取得
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // バイト配列としてハイパーリンクのサウンドを抽出
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

ハイパーリンクの再生サウンドを表します。読み取り/書き込み [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 最初の形状ハイパーリンクを取得
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // ハイパーリンクのサウンドをバイト配列で抽出
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

ハイパーリンクの色のソースを表します（スタイルまたは部分フォーマット）。読み取り/書き込み [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**戻り値:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

ハイパーリンクの色のソースを表します（スタイルまたは部分フォーマット）。読み取り/書き込み [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

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
| obj | java.lang.Object | 現在の Hyperlink と比較する Hyperlink。 |

**戻り値:**
boolean - **true** 指定された Hyperlink が現在の Hyperlink と等しい場合; それ以外の場合は **false**。
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

2 つの Hyperlink インスタンスが等しいかどうかを決定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 現在の Hyperlink と比較する Hyperlink。 |

**戻り値:**
boolean - **true** 指定された Hyperlink が現在の Hyperlink と等しい場合; それ以外の場合は **false**。
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

2 つのハイパーリンクが等しいかテストします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | テスト対象の最初のハイパーリンク。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | テスト対象の2番目のハイパーリンク。 |

**戻り値:**
boolean - **true** if hyperlinks are equal.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

2 つのハイパーリンクが等しくないかテストします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | テスト対象の最初のハイパーリンク。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | テスト対象の2番目のハイパーリンク。 |

**戻り値:**
boolean - ハイパーリンクが等しい場合は **false**。
### hashCode() {#hashCode--}
```
public int hashCode()
```

ハッシュテーブルなどのハッシュアルゴリズムやデータ構造で使用できる、特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - URL のハッシュコード。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject