---
title: IMarker
second_title: Aspose.Slides for Android via Java API Reference
description: チャートのマーカーを表します。
type: docs
url: /ja/com.aspose.slides/imarker/
---```
public interface IMarker
```

チャートのマーカーを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSymbol()](#getSymbol--) | 折れ線グラフ、散布図、またはレーダーグラフにおけるマーカーのスタイルを表します。 |
| [setSymbol(int value)](#setSymbol-int-) | 折れ線グラフ、散布図、またはレーダーグラフにおけるマーカーのスタイルを表します。 |
| [getFormat()](#getFormat--) | マーカーの塗りつぶしを取得します。 |
| [getSize()](#getSize--) | 折れ線グラフ、散布図、またはレーダーグラフにおけるマーカーのサイズを表します。 |
| [setSize(int value)](#setSize-int-) | 折れ線グラフ、散布図、またはレーダーグラフにおけるマーカーのサイズを表します。 |
### getSymbol() {#getSymbol--}
```
public abstract int getSymbol()
```

折れ線グラフ、散布図、またはレーダーグラフにおけるマーカーのスタイルを表します。読み取り/書き込み [MarkerStyleType](../../com.aspose.slides/markerstyletype)。

**戻り値:**
int
### setSymbol(int value) {#setSymbol-int-}
```
public abstract void setSymbol(int value)
```

折れ線グラフ、散布図、またはレーダーグラフにおけるマーカーのスタイルを表します。読み取り/書き込み [MarkerStyleType](../../com.aspose.slides/markerstyletype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

マーカーの塗りつぶしを取得します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public abstract int getSize()
```

折れ線グラフ、散布図、またはレーダーグラフにおけるマーカーのサイズを表します。読み取り/書き込み int。

**戻り値:**
int
### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```

折れ線グラフ、散布図、またはレーダーグラフにおけるマーカーのサイズを表します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |