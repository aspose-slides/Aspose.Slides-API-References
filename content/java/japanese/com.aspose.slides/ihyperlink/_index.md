---
title: IHyperlink
second_title: Aspose.Slides for Java API リファレンス
description: ハイパーリンクを表します。
type: docs
url: /ja/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

ハイパーリンクを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getActionType()](#getActionType--) | HyperLinkEx のアクションのタイプを返します。 |
| [getExternalUrl()](#getExternalUrl--) | 外部 URL を指定します。このプロパティが null でなくなると、プロパティ TargetSlide は null になります。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 実際のコンテンツに関係なく、この部分に設定されたハイパーリンクを表します。 |
| [getTargetSlide()](#getTargetSlide--) | HyperlinkEx が特定のスライドを対象としている場合、そのスライドを返します。 |
| [getTargetFrame()](#getTargetFrame--) | 親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内のフレームを返します。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内のフレームを返します。 |
| [getTooltip()](#getTooltip--) | 親ハイパーリンクに関連付けられたユーザーインターフェイスに表示される可能性のある文字列を返します。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 親ハイパーリンクに関連付けられたユーザーインターフェイスに表示される可能性のある文字列を返します。 |
| [getHistory()](#getHistory--) | 親ハイパーリンクが呼び出されたときに、その対象が閲覧済みハイパーリンクのリストに追加されるかどうかを決定します。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 親ハイパーリンクが呼び出されたときに、その対象が閲覧済みハイパーリンクのリストに追加されるかどうかを決定します。 |
| [getHighlightClick()](#getHighlightClick--) | クリック時にハイパーリンクをハイライト表示すべきかどうかを決定します。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | クリック時にハイパーリンクをハイライト表示すべきかどうかを決定します。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | ハイパーリンククリック時にサウンドを停止すべきかどうかを決定します。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | ハイパーリンククリック時にサウンドを停止すべきかどうかを決定します。 |
| [getSound()](#getSound--) | ハイパーリンクの再生サウンドを表します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | ハイパーリンクの再生サウンドを表します。 |
| [getColorSource()](#getColorSource--) | ハイパーリンクの色のソースを表します（スタイルまたは部分書式のいずれか）。 |
| [setColorSource(int value)](#setColorSource-int-) | ハイパーリンクの色のソースを表します（スタイルまたは部分書式のいずれか）。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 2 つの Hyperlink インスタンスが等しいかどうかを判断します。 |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

HyperLinkEx のアクションのタイプを返します。読み取り専用 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

**戻り値:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

外部 URL を指定します。このプロパティが null でなくなると、プロパティ TargetSlide は null になります。読み取り専用 String。

**戻り値:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

実際のコンテンツに関係なく、この部分に設定されたハイパーリンクを表します。

--------------------

PowerPoint はリンクとその部分テキストに対して特別な動作をします。リンクの実際のアドレスとは異なる有効な URL 形式でハイパーリンク用テキストを作成できます。この場合、編集ウィンドウでリンクを表示すると、テキスト部分に合わせて変更されます。このプロパティはハイパーリンクの元の値を表します。

**戻り値:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

HyperlinkEx が特定のスライドを対象としている場合、そのスライドを返します。プロパティが null でなくなると、プロパティ ExternalUrl は null になります。読み取り専用 [ISlide](../../com.aspose.slides/islide)。

**戻り値:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内のフレームを返します。読み書き可能 String。

**戻り値:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内のフレームを返します。読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

親ハイパーリンクに関連付けられたユーザーインターフェイスに表示される可能性のある文字列を返します。読み書き可能 String。

**戻り値:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

親ハイパーリンクに関連付けられたユーザーインターフェイスに表示される可能性のある文字列を返します。読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

親ハイパーリンクが呼び出されたときに、その対象が閲覧済みハイパーリンクのリストに追加されるかどうかを決定します。読み書き可能 boolean。

**戻り値:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

親ハイパーリンクが呼び出されたときに、その対象が閲覧済みハイパーリンクのリストに追加されるかどうかを決定します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

クリック時にハイパーリンクをハイライト表示すべきかどうかを決定します。読み書き可能 boolean。

**戻り値:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

クリック時にハイパーリンクをハイライト表示すべきかどうかを決定します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

ハイパーリンククリック時にサウンドを停止すべきかどうかを決定します。読み書き可能 boolean。

**戻り値:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

ハイパーリンククリック時にサウンドを停止すべきかどうかを決定します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

ハイパーリンクの再生サウンドを表します。読み書き可能 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 最初のシェイプのハイパーリンクを取得する
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // ハイパーリンクのサウンドをバイト配列で抽出する
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
public abstract void setSound(IAudio value)
```

ハイパーリンクの再生サウンドを表します。読み書き可能 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 最初のシェイプのハイパーリンクを取得する
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // ハイパーリンクのサウンドをバイト配列で抽出する
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
public abstract int getColorSource()
```

ハイパーリンクの色のソースを表します（スタイルまたは部分書式のいずれか）。読み書き可能 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**戻り値:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

ハイパーリンクの色のソースを表します（スタイルまたは部分書式のいずれか）。読み書き可能 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

2 つの Hyperlink インスタンスが等しいかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 比較対象の Hyperlink。 |

**戻り値:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.