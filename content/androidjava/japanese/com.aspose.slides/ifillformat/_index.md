---
title: IFillFormat
second_title: Java APIリファレンスによる Android 用 Aspose.Slides
description: 塗りつぶし書式オプションを表します。
type: docs
url: /ja/com.aspose.slides/ifillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

塗りつぶし書式オプションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillType()](#getFillType--) | 塗りつぶしのタイプを取得または設定します。 |
| [setFillType(byte value)](#setFillType-byte-) | 塗りつぶしのタイプを取得または設定します。 |
| [getSolidFillColor()](#getSolidFillColor--) | 塗りつぶしの色を返します。 |
| [getGradientFormat()](#getGradientFormat--) | グラデーション塗りつぶし形式を返します。 |
| [getPatternFormat()](#getPatternFormat--) | パターン塗りつぶし形式を返します。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 画像塗りつぶし形式を返します。 |
| [getRotateWithShape()](#getRotateWithShape--) | 塗りつぶしがシェイプとともに回転すべきかどうかを判断します。 |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 塗りつぶしがシェイプとともに回転すべきかどうかを判断します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な塗りつぶし書式データを取得します。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

塗りつぶしのタイプを取得または設定します。 読み取り/書き込み [FillType](../../com.aspose.slides/filltype)。

**戻り値:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

塗りつぶしのタイプを取得または設定します。 読み取り/書き込み [FillType](../../com.aspose.slides/filltype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

塗りつぶしの色を返します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

グラデーション塗りつぶし形式を返します。 読み取り専用 [IGradientFormat](../../com.aspose.slides/igradientformat)。

**戻り値:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

パターン塗りつぶし形式を返します。 読み取り専用 [IPatternFormat](../../com.aspose.slides/ipatternformat)。

**戻り値:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

画像塗りつぶし形式を返します。 読み取り専用 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**戻り値:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

塗りつぶしがシェイプとともに回転すべきかどうかを判断します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

塗りつぶしがシェイプとともに回転すべきかどうかを判断します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

継承が適用された有効な塗りつぶし書式データを取得します。

**戻り値:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。