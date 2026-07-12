---
title: IDrawingGuide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an adjustable drawing guide.
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
| [getPosition()](#getPosition--) | スライドの左上隅からポイント単位で、描画ガイドの位置を取得または設定します。 |
| [setPosition(float value)](#setPosition-float-) | スライドの左上隅からポイント単位で、描画ガイドの位置を取得または設定します。 |
| [getColor()](#getColor--) | 描画ガイドの色を取得または設定します。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 描画ガイドの色を取得または設定します。 |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

描画ガイドの向きを取得または設定します。読み書き [Orientation](../../com.aspose.slides/orientation)。

**戻り値:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

描画ガイドの向きを取得または設定します。読み書き [Orientation](../../com.aspose.slides/orientation)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

スライドの左上隅からポイント単位で、描画ガイドの位置を取得または設定します。読み書き float.

--------------------

典型的な値の範囲は、水平ガイドの場合はスライドの高さの 0 から、垂直ガイドの場合はスライドの幅の 0 からです。

**戻り値:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

スライドの左上隅からポイント単位で、描画ガイドの位置を取得または設定します。読み書き float.

--------------------

典型的な値の範囲は、水平ガイドの場合はスライドの高さの 0 から、垂直ガイドの場合はスライドの幅の 0 からです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

描画ガイドの色を取得または設定します。読み書き java.lang.Integer。

**戻り値:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

描画ガイドの色を取得または設定します。読み書き java.lang.Integer。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Integer |  |