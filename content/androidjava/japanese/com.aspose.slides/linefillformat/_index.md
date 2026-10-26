---
title: LineFillFormat
second_title: Java API リファレンス経由の Android 用 Aspose.Slides
description: 線の塗りつぶしに関するプロパティを表します。
type: docs
url: /ja/com.aspose.slides/linefillformat/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

ラインの塗りつぶしに関するプロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | 塗りつぶしタイプを取得または設定します。 |
| [setFillType(byte value)](#setFillType-byte-) | 塗りつぶしタイプを取得または設定します。 |
| [getRotateWithShape()](#getRotateWithShape--) | 塗りつぶしがシェイプとともに回転すべきかどうかを決定します。 |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 塗りつぶしがシェイプとともに回転すべきかどうかを決定します。 |
| [getSolidFillColor()](#getSolidFillColor--) | 単色塗りつぶしの色を返します。 |
| [getGradientFormat()](#getGradientFormat--) | グラデーション塗りつぶしの形式を返します。 |
| [getPatternFormat()](#getPatternFormat--) | パターン塗りつぶしの形式を返します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long.

**戻り値:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

塗りつぶしタイプを取得または設定します。 読み書き可能 [FillType](../../com.aspose.slides/filltype)。

**戻り値:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

塗りつぶしタイプを取得または設定します。 読み書き可能 [FillType](../../com.aspose.slides/filltype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

塗りつぶしがシェイプとともに回転すべきかどうかを決定します。 読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

塗りつぶしがシェイプとともに回転すべきかどうかを決定します。 読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

単色塗りつぶしの色を返します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

グラデーション塗りつぶしの形式を返します。 読み取り専用 [IGradientFormat](../../com.aspose.slides/igradientformat)。

**戻り値:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

パターン塗りつぶしの形式を返します。 読み取り専用 [IPatternFormat](../../com.aspose.slides/ipatternformat)。

**戻り値:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)