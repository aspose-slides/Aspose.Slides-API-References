---
title: NormalViewProperties
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: 通常ビューのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/normalviewproperties/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

通常ビューのプロパティを表します。通常ビューは、スライド自体、サイドコンテンツ領域、下部コンテンツ領域の3つのコンテンツ領域で構成されます。

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //プレゼンテーション ファイルを表すプレゼンテーション オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | アプリケーションが通常ビュー モードの任意のコンテンツ領域でアウトライン コンテンツを表示する場合に、アイコンを表示すべきかどうかを指定します。 |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | アプリケーションが通常ビュー モードの任意のコンテンツ領域でアウトライン コンテンツを表示する場合に、アイコンを表示すべきかどうかを指定します。 |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | サイド領域が十分に小さい場合に、垂直スプリッタが最小化状態にスナップすべきかどうかを指定します。 |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | サイド領域が十分に小さい場合に、垂直スプリッタが最小化状態にスナップすべきかどうかを指定します。 |
| [getVerticalBarState()](#getVerticalBarState--) | 垂直スプリッタ バーの表示状態を指定します。 |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | 垂直スプリッタ バーの表示状態を指定します。 |
| [getHorizontalBarState()](#getHorizontalBarState--) | 水平スプリッタ バーの表示状態を指定します。 |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | 水平スプリッタ バーの表示状態を指定します。 |
| [getPreferSingleView()](#getPreferSingleView--) | ユーザーが3つのコンテンツ領域を持つ標準的な通常ビューではなく、ウィンドウ全体で単一コンテンツ領域を表示することを好むかどうかを指定します。 |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | ユーザーが3つのコンテンツ領域を持つ標準的な通常ビューではなく、ウィンドウ全体で単一コンテンツ領域を表示することを好むかどうかを指定します。 |
| [getRestoredLeft()](#getRestoredLeft--) | この要素は、変動する復元サイズ（最小化でも最大化でもない）の場合の、通常ビューのサイドコンテンツ領域のサイズを指定します。 |
| [getRestoredTop()](#getRestoredTop--) | この要素は、変動する復元サイズ（最小化でも最大化でもない）の場合の、通常ビューの上部スライド領域のサイズを指定します。 |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

アプリケーションが通常ビュー モードの任意のコンテンツ領域でアウトライン コンテンツを表示する場合に、アイコンを表示すべきかどうかを指定します。読み書き可能な boolean。

**戻り値:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

アプリケーションが通常ビュー モードの任意のコンテンツ領域でアウトライン コンテンツを表示する場合に、アイコンを表示すべきかどうかを指定します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

サイド領域が十分に小さい場合に、垂直スプリッタが最小化状態にスナップすべきかどうかを指定します。読み書き可能な boolean。

**戻り値:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

サイド領域が十分に小さい場合に、垂直スプリッタが最小化状態にスナップすべきかどうかを指定します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

垂直スプリッタ バーの表示状態を指定します。垂直スプリッタ バーはスライドとサイドコンテンツ領域を分割します。

**戻り値:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

垂直スプリッタ バーの表示状態を指定します。垂直スプリッタ バーはスライドとサイドコンテンツ領域を分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

水平スプリッタ バーの表示状態を指定します。水平スプリッタ バーはスライドとスライド下部のコンテンツ領域を分割します。

**戻り値:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

水平スプリッタ バーの表示状態を指定します。水平スプリッタ バーはスライドとスライド下部のコンテンツ領域を分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

ユーザーが3つのコンテンツ領域を持つ標準的な通常ビューではなく、ウィンドウ全体で単一コンテンツ領域を表示することを好むかどうかを指定します。有効にすると、アプリケーションはウィンドウ全体に1つのコンテンツ領域を表示することを選択できるようになります。読み書き可能な boolean。

**戻り値:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

ユーザーが3つのコンテンツ領域を持つ標準的な通常ビューではなく、ウィンドウ全体で単一コンテンツ領域を表示することを好むかどうかを指定します。有効にすると、アプリケーションはウィンドウ全体に1つのコンテンツ領域を表示することを選択できるようになります。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

この要素は、変動する復元サイズ（最小化でも最大化でもない）の場合の、通常ビューのサイドコンテンツ領域のサイズを指定します。読み取り専用 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**戻り値:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

この要素は、変動する復元サイズ（最小化でも最大化でもない）の場合の、通常ビューの上部スライド領域のサイズを指定します。読み取り専用 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**戻り値:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)