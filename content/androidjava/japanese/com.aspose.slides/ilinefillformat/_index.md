---
title: ILineFillFormat
second_title: Aspose.Slides for Android の Java API リファレンス
description: ラインの塗りつぶしに関するプロパティを表します。
type: docs
url: /ja/com.aspose.slides/ilinefillformat/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

ラインの塗りつぶしに関するプロパティを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | 塗りつぶしタイプを取得または設定します。 |
| [setFillType(byte value)](#setFillType-byte-) | 塗りつぶしタイプを取得または設定します。 |
| [getSolidFillColor()](#getSolidFillColor--) | 単色塗りつぶしの色を取得します。 |
| [getGradientFormat()](#getGradientFormat--) | グラデーション塗りつぶしの書式を取得します。 |
| [getPatternFormat()](#getPatternFormat--) | パターン塗りつぶしの書式を取得します。 |
| [getRotateWithShape()](#getRotateWithShape--) | 塗りつぶしがシェイプとともに回転するかどうかを決定します。 |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 塗りつぶしがシェイプとともに回転するかどうかを決定します。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

塗りつぶしタイプを取得または設定します。 読み取り/書き込み [FillType](../../com.aspose.slides/filltype)。

**戻り値:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

塗りつぶしタイプを取得または設定します。 読み取り/書き込み [FillType](../../com.aspose.slides/filltype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

単色塗りつぶしの色を取得します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

グラデーション塗りつぶしの書式を取得します。 読み取り専用 [IGradientFormat](../../com.aspose.slides/igradientformat)。

**戻り値:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

パターン塗りつぶしの書式を取得します。 読み取り専用 [IPatternFormat](../../com.aspose.slides/ipatternformat)。

**戻り値:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

塗りつぶしがシェイプとともに回転するかどうかを決定します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

塗りつぶしがシェイプとともに回転するかどうかを決定します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |