---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /ja/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

通常ビューのプロパティを表します。通常ビューは 3 つのコンテンツ領域で構成されます。スライド自体、サイド コンテンツ領域、そして下部コンテンツ領域です。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | 通常ビュー モードの任意のコンテンツ領域でアウトライン コンテンツを表示する場合に、アプリケーションがアイコンを表示すべきかどうかを指定します。 |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | 通常ビュー モードの任意のコンテンツ領域でアウトライン コンテンツを表示する場合に、アプリケーションがアイコンを表示すべきかどうかを指定します。 |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | サイド領域が十分に小さい場合に、垂直スプリッタが最小化状態にスナップすべきかどうかを指定します。 |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | サイド領域が十分に小さい場合に、垂直スプリッタが最小化状態にスナップすべきかどうかを指定します。 |
| [getVerticalBarState()](#getVerticalBarState--) | 垂直スプリッタ バーが表示される状態を指定します。 |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | 垂直スプリッタ バーが表示される状態を指定します。 |
| [getHorizontalBarState()](#getHorizontalBarState--) | 水平スプリッタ バーが表示される状態を指定します。 |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | 水平スプリッタ バーが表示される状態を指定します。 |
| [getPreferSingleView()](#getPreferSingleView--) | ユーザーが 3 つのコンテンツ領域を持つ標準の通常ビューではなく、全画面単一コンテンツ領域を表示することを好むかどうかを指定します。 |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | ユーザーが 3 つのコンテンツ領域を持つ標準の通常ビューではなく、全画面単一コンテンツ領域を表示することを好むかどうかを指定します。 |
| [getRestoredLeft()](#getRestoredLeft--) | この要素は、領域が可変の復元サイズ（最小化でも最大化でもない）である場合の、通常ビューのサイド コンテンツ領域のサイズを指定します。 |
| [getRestoredTop()](#getRestoredTop--) | この要素は、領域が可変の復元サイズ（最小化でも最大化でもない）である場合の、通常ビューの上部スライド領域のサイズを指定します。 |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

通常ビュー モードの任意のコンテンツ領域でアウトライン コンテンツを表示する場合に、アプリケーションがアイコンを表示すべきかどうかを指定します。読み書き可能な boolean。

**戻り値:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

通常ビュー モードの任意のコンテンツ領域でアウトライン コンテンツを表示する場合に、アプリケーションがアイコンを表示すべきかどうかを指定します。読み書き可能な boolean。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

サイド領域が十分に小さい場合に、垂直スプリッタが最小化状態にスナップすべきかどうかを指定します。読み書き可能な boolean。

**戻り値:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

サイド領域が十分に小さい場合に、垂直スプリッタが最小化状態にスナップすべきかどうかを指定します。読み書き可能な boolean。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

垂直スプリッタ バーが表示される状態を指定します。垂直スプリッタ バーはスライドとサイド コンテンツ領域を分離します。

**戻り値:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

垂直スプリッタ バーが表示される状態を指定します。垂直スプリッタ バーはスライドとサイド コンテンツ領域を分離します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

水平スプリッタ バーが表示される状態を指定します。水平スプリッタ バーはスライドとスライド下のコンテンツ領域を分離します。

**戻り値:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

水平スプリッタ バーが表示される状態を指定します。水平スプリッタ バーはスライドとスライド下のコンテンツ領域を分離します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

ユーザーが 3 つのコンテンツ領域を持つ標準の通常ビューではなく、全画面単一コンテンツ領域を表示することを好むかどうかを指定します。有効にすると、アプリケーションはコンテンツ領域のうちの一つをウィンドウ全体に表示することを選択できるようになります。読み書き可能な boolean。

**戻り値:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

ユーザーが 3 つのコンテンツ領域を持つ標準の通常ビューではなく、全画面単一コンテンツ領域を表示することを好むかどうかを指定します。有効にすると、アプリケーションはコンテンツ領域のうちの一つをウィンドウ全体に表示することを選択できるようになります。読み書き可能な boolean。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

この要素は、領域が可変の復元サイズ（最小化でも最大化でもない）である場合の、通常ビューのサイド コンテンツ領域のサイズを指定します。読み取り専用 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**戻り値:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

この要素は、領域が可変の復元サイズ（最小化でも最大化でもない）である場合の、通常ビューの上部スライド領域のサイズを指定します。読み取り専用 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**戻り値:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)