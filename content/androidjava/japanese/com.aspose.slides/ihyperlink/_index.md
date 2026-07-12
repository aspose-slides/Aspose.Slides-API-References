---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a hyperlink.
type: docs
url: /ja/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

ハイパーリンクを表します。

## メソッド

| Method | Description |
| --- | --- |
| [getActionType()](#getActionType--) | HyperLinkEx のアクションの型を返します。 |
| [getExternalUrl()](#getExternalUrl--) | 外部 URL を指定します。このプロパティが null でなくなると、プロパティ TargetSlide は null になります。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | この部分の実際の内容に関係なく、この部分に設定されたハイパーリンクを表します。 |
| [getTargetSlide()](#getTargetSlide--) | HyperlinkEx が特定のスライドを対象としている場合、そのスライドを返します。 |
| [getTargetFrame()](#getTargetFrame--) | 親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内の対象フレームを返します。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内の対象フレームを返します。 |
| [getTooltip()](#getTooltip--) | 親ハイパーリンクに関連付けられたユーザーインターフェイスに表示される可能性のある文字列を返します。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 親ハイパーリンクに関連付けられたユーザーインターフェイスに表示される可能性のある文字列を返します。 |
| [getHistory()](#getHistory--) | 呼び出されたときに、親ハイパーリンクの対象を閲覧済みハイパーリンクのリストに追加するかどうかを決定します。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 呼び出されたときに、親ハイパーリンクの対象を閲覧済みハイパーリンクのリストに追加するかどうかを決定します。 |
| [getHighlightClick()](#getHighlightClick--) | クリック時にハイパーリンクをハイライト表示するかどうかを決定します。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | クリック時にハイパーリンクをハイライト表示するかどうかを決定します。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | ハイパーリンクをクリックしたときにサウンドを停止するかどうかを決定します。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | ハイパーリンクをクリックしたときにサウンドを停止するかどうかを決定します。 |
| [getSound()](#getSound--) | ハイパーリンクの再生中サウンドを表します。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | ハイパーリンクの再生中サウンドを表します。 |
| [getColorSource()](#getColorSource--) | ハイパーリンクの色のソースを表します（スタイルまたは部分フォーマット）。 |
| [setColorSource(int value)](#setColorSource-int-) | ハイパーリンクの色のソースを表します（スタイルまたは部分フォーマット）。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 2 つの Hyperlink インスタンスが等しいかどうかを判断します。 |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

HyperLinkEx のアクションの型を返します。読み取り専用 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

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

この部分の実際の内容に関係なく、この部分に設定されたハイパーリンクを表します。

--------------------

PowerPoint はリンクとそれに対応するテキストの扱いに特有の動作をします。リンクの実際のアドレスとは異なる有効な URL 形式でハイパーリンク用のテキストを作成できます。この場合、編集ウィンドウでリンクを表示すると、テキスト部分に合わせて変更されます。このプロパティはハイパーリンクの元の値を表します。

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

親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内の対象フレームを返します。読み書き可能 String。

**戻り値:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内の対象フレームを返します。読み書き可能 String。

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

呼び出されたときに、親ハイパーリンクの対象を閲覧済みハイパーリンクのリストに追加するかどうかを決定します。読み書き可能 boolean。

**戻り値:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

呼び出されたときに、親ハイパーリンクの対象を閲覧済みハイパーリンクのリストに追加するかどうかを決定します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

クリック時にハイパーリンクをハイライト表示するかどうかを決定します。読み書き可能 boolean。

**戻り値:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

クリック時にハイパーリンクをハイライト表示するかどうかを決定します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

ハイパーリンクをクリックしたときにサウンドを停止するかどうかを決定します。読み書き可能 boolean。

**戻り値:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

ハイパーリンクをクリックしたときにサウンドを停止するかどうかを決定します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

ハイパーリンクの再生中サウンドを表します。読み書き可能 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Get the first shape hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extract the hyperlink sound in byte array
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

ハイパーリンクの再生中サウンドを表します。読み書き可能 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Get the first shape hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extract the hyperlink sound in byte array
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

ハイパーリンクの色のソースを表します（スタイルまたは部分フォーマット）。読み書き可能 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**戻り値:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

ハイパーリンクの色のソースを表します（スタイルまたは部分フォーマット）。読み書き可能 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

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
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 現在の Hyperlink と比較する Hyperlink。 |

**戻り値:**
boolean - 指定された Hyperlink が現在の Hyperlink と等しい場合は **true**、それ以外の場合は **false**。