---
title: IColorFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションで使用される色を表します。
type: docs
url: /ja/com.aspose.slides/icolorformat/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

プレゼンテーションで使用される色を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColorType()](#getColorType--) | カラー定義方法を取得または設定します。 |
| [setColorType(int value)](#setColorType-int-) | カラー定義方法を取得または設定します。 |
| [getColor()](#getColor--) | すべてのカラー変換を適用した結果の色を返します。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | すべてのカラー変換を適用した結果の色を返します。 |
| [getPresetColor()](#getPresetColor--) | カラープリセットを取得または設定します。 |
| [setPresetColor(int value)](#setPresetColor-int-) | カラープリセットを取得または設定します。 |
| [getSystemColor()](#getSystemColor--) | システム カラーテーブルで識別される色を取得または設定します。 |
| [setSystemColor(int value)](#setSystemColor-int-) | システム カラーテーブルで識別される色を取得または設定します。 |
| [getSchemeColor()](#getSchemeColor--) | カラースキームで識別される色を取得または設定します。 |
| [setSchemeColor(int value)](#setSchemeColor-int-) | カラースキームで識別される色を取得または設定します。 |
| [getR()](#getR--) | 赤成分を取得または設定します。 |
| [setR(byte value)](#setR-byte-) | 赤成分を取得または設定します。 |
| [getG()](#getG--) | 緑成分を取得または設定します。 |
| [setG(byte value)](#setG-byte-) | 緑成分を取得または設定します。 |
| [getB()](#getB--) | 青成分を取得または設定します。 |
| [setB(byte value)](#setB-byte-) | 青成分を取得または設定します。 |
| [getFloatR()](#getFloatR--) | 赤成分を取得または設定します。 |
| [setFloatR(float value)](#setFloatR-float-) | 赤成分を取得または設定します。 |
| [getFloatG()](#getFloatG--) | 緑成分を取得または設定します。 |
| [setFloatG(float value)](#setFloatG-float-) | 緑成分を取得または設定します。 |
| [getFloatB()](#getFloatB--) | 青成分を取得または設定します。 |
| [setFloatB(float value)](#setFloatB-float-) | 青成分を取得または設定します。 |
| [getHue()](#getHue--) | HSL 表現の色相成分を取得または設定します。 |
| [setHue(float value)](#setHue-float-) | HSL 表現の色相成分を取得または設定します。 |
| [getSaturation()](#getSaturation--) | HSL 表現の彩度成分を取得または設定します。 |
| [setSaturation(float value)](#setSaturation-float-) | HSL 表現の彩度成分を取得または設定します。 |
| [getLuminance()](#getLuminance--) | HSL 表現の明度成分を取得または設定します。 |
| [setLuminance(float value)](#setLuminance-float-) | HSL 表現の明度成分を取得または設定します。 |
| [getColorTransform()](#getColorTransform--) | カラーに適用されたカラー変換のコレクションを返します。 |
| [toString(int format)](#toString-int-) | 現在のカラー形式を表す文字列を返します。 |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | 「color」からカラー形式をコピーします。 |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

カラー定義方法を取得または設定します。 読み取り/書き込み [ColorType](../../com.aspose.slides/colortype)。

**戻り値:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

カラー定義方法を取得または設定します。 読み取り/書き込み [ColorType](../../com.aspose.slides/colortype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

すべてのカラー変換を適用した結果の色を返します。 RGB カラーを設定し、すべてのカラー変換をクリアします。 読み取り/書き込み java.lang.Integer。

**戻り値:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

すべてのカラー変換を適用した結果の色を返します。 RGB カラーを設定し、すべてのカラー変換をクリアします。 読み取り/書き込み java.lang.Integer。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

カラープリセットを取得または設定します。 読み取り/書き込み [PresetColor](../../com.aspose.slides/presetcolor)。

**戻り値:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

カラープリセットを取得または設定します。 読み取り/書き込み [PresetColor](../../com.aspose.slides/presetcolor)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

システム カラーテーブルで識別される色を取得または設定します。 読み取り/書き込み [SystemColor](../../com.aspose.slides/systemcolor)。

**戻り値:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

システム カラーテーブルで識別される色を取得または設定します。 読み取り/書き込み [SystemColor](../../com.aspose.slides/systemcolor)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

カラースキームで識別される色を取得または設定します。 読み取り/書き込み [SchemeColor](../../com.aspose.slides/schemecolor)。

**戻り値:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

カラースキームで識別される色を取得または設定します。 読み取り/書き込み [SchemeColor](../../com.aspose.slides/schemecolor)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

赤成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み byte。

**戻り値:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

赤成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み byte。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

緑成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み byte。

**戻り値:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

緑成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み byte。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

青成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み byte。

**戻り値:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

青成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み byte。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

赤成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

赤成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

緑成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

緑成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

青成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

青成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

HSL 表現の色相成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

HSL 表現の色相成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

HSL 表現の彩度成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

HSL 表現の彩度成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

HSL 表現の明度成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

HSL 表現の明度成分を取得または設定します。 すべてのカラー変換は無視されます。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

カラーに適用されたカラー変換のコレクションを返します。 読み取り専用 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)。

**戻り値:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

現在のカラー形式を表す String を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | int | カラー文字列形式の種類。 |

**戻り値:**
java.lang.String - 現在のカラー形式を表す文字列。
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

「color」からカラー形式をコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |