---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: 調整可能な描画ガイドを表します。
type: docs
url: /ja/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

調整可能な描画ガイドを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOrientation()](#getOrientation--) | 描画ガイドの向きを取得または設定します。 |
| [setOrientation(byte value)](#setOrientation-byte-) | 描画ガイドの向きを取得または設定します。 |
| [getPosition()](#getPosition--) | スライドの左上隅からポイント単位で描画ガイドの位置を取得または設定します。 |
| [setPosition(float value)](#setPosition-float-) | スライドの左上隅からポイント単位で描画ガイドの位置を取得または設定します。 |
| [getColor()](#getColor--) | 描画ガイドの色を取得または設定します。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 描画ガイドの色を取得または設定します。 |

### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

描画ガイドの向きを取得または設定します。読み取り/書き込み [Orientation](../../com.aspose.slides/orientation)。

**戻り値:**
byte

### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

描画ガイドの向きを取得または設定します。読み取り/書き込み [Orientation](../../com.aspose.slides/orientation)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

スライドの左上隅からポイント単位で描画ガイドの位置を取得または設定します。読み取り/書き込み float。

--------------------

一般的な値の範囲は、水平ガイドの場合は0からスライドの高さまで、垂直ガイドの場合は0からスライドの幅までです。

**戻り値:**
float

### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

スライドの左上隅からポイント単位で描画ガイドの位置を取得または設定します。読み取り/書き込み float。

--------------------

一般的な値の範囲は、水平ガイドの場合は0からスライドの高さまで、垂直ガイドの場合は0からスライドの幅までです。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

描画ガイドの色を取得または設定します。読み取り/書き込み java.awt.Color。

**戻り値:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

描画ガイドの色を取得または設定します。読み取り/書き込み java.awt.Color。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.Color |  |