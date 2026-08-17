---
title: IColorFormat
second_title: Aspose.Slides for Java API リファレンス
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
| [getColorType()](#getColorType--) | 色定義方法を取得または設定します。 |
| [setColorType(int value)](#setColorType-int-) | 色定義方法を取得または設定します。 |
| [getColor()](#getColor--) | すべての色変換を適用した結果の色を取得します。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | すべての色変換を適用した結果の色を取得します。 |
| [getPresetColor()](#getPresetColor--) | カラーのプリセットを取得または設定します。 |
| [setPresetColor(int value)](#setPresetColor-int-) | カラーのプリセットを取得または設定します。 |
| [getSystemColor()](#getSystemColor--) | システム カラーテーブルで識別される色を取得または設定します。 |
| [setSystemColor(int value)](#setSystemColor-int-) | システム カラーテーブルで識別される色を取得または設定します。 |
| [getSchemeColor()](#getSchemeColor--) | カラースキームで識別される色を取得または設定します。 |
| [setSchemeColor(int value)](#setSchemeColor-int-) | カラースキームで識別される色を取得または設定します。 |
| [getR()](#getR--) | 色の赤成分を取得または設定します。 |
| [setR(byte value)](#setR-byte-) | 色の赤成分を取得または設定します。 |
| [getG()](#getG--) | 色の緑成分を取得または設定します。 |
| [setG(byte value)](#setG-byte-) | 色の緑成分を取得または設定します。 |
| [getB()](#getB--) | 色の青成分を取得または設定します。 |
| [setB(byte value)](#setB-byte-) | 色の青成分を取得または設定します。 |
| [getFloatR()](#getFloatR--) | 色の赤成分を取得または設定します。 |
| [setFloatR(float value)](#setFloatR-float-) | 色の赤成分を取得または設定します。 |
| [getFloatG()](#getFloatG--) | 色の緑成分を取得または設定します。 |
| [setFloatG(float value)](#setFloatG-float-) | 色の緑成分を取得または設定します。 |
| [getFloatB()](#getFloatB--) | 色の青成分を取得または設定します。 |
| [setFloatB(float value)](#setFloatB-float-) | 色の青成分を取得または設定します。 |
| [getHue()](#getHue--) | HSL 表現における色の色相成分を取得または設定します。 |
| [setHue(float value)](#setHue-float-) | HSL 表現における色の色相成分を取得または設定します。 |
| [getSaturation()](#getSaturation--) | HSL 表現における色の彩度成分を取得または設定します。 |
| [setSaturation(float value)](#setSaturation-float-) | HSL 表現における色の彩度成分を取得または設定します。 |
| [getLuminance()](#getLuminance--) | HSL 表現における色の輝度成分を取得または設定します。 |
| [setLuminance(float value)](#setLuminance-float-) | HSL 表現における色の輝度成分を取得または設定します。 |
| [getColorTransform()](#getColorTransform--) | 色に適用された色変換のコレクションを取得します。 |
| [toString(int format)](#toString-int-) | 現在の色形式を表す文字列を取得します。 |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | "color" から色形式をコピーします。 |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

色定義方法を取得または設定します。 読み取り/書き込み [ColorType](../../com.aspose.slides/colortype)。

**戻り値:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

色定義方法を取得または設定します。 読み取り/書き込み [ColorType](../../com.aspose.slides/colortype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

すべての色変換を適用した結果の色を取得します。 RGB 色を設定し、すべての色変換をクリアします。 読み取り/書き込み java.awt.Color。

**戻り値:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

すべての色変換を適用した結果の色を取得します。 RGB 色を設定し、すべての色変換をクリアします。 読み取り/書き込み java.awt.Color。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.Color |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

カラーのプリセットを取得または設定します。 読み取り/書き込み [PresetColor](../../com.aspose.slides/presetcolor)。

**戻り値:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

カラーのプリセットを取得または設定します。 読み取り/書き込み [PresetColor](../../com.aspose.slides/presetcolor)。

**パラメータ:**
| パラメータ | 型 | 説明 |
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

**パラメータ:**
| パラメータ | 型 | 説明 |
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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

色の赤成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み byte。

**戻り値:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

色の赤成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み byte。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

色の緑成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み byte。

**戻り値:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

色の緑成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み byte。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

色の青成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み byte。

**戻り値:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

色の青成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み byte。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

色の赤成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

色の赤成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

色の緑成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

色の緑成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

色の青成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

色の青成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

HSL 表現における色の色相成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

HSL 表現における色の色相成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

HSL 表現における色の彩度成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

HSL 表現における色の彩度成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

HSL 表現における色の輝度成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**戻り値:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

HSL 表現における色の輝度成分を取得または設定します。 すべての色変換は無視されます。 読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

色に適用された色変換のコレクションを取得します。 読み取り専用 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)。

**戻り値:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

現在の色形式を表す文字列を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | int | 色文字列形式の種類。 |

**戻り値:**
java.lang.String - 現在の色形式を表す文字列。
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

"color" から色形式をコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |