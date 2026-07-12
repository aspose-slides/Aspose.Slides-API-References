---
title: ColorFormat
second_title: Java API リファレンスを使用した Android 向け Aspose.Slides
description: プレゼンテーションで使用される色を表します。
type: docs
url: /ja/com.aspose.slides/colorformat/
---
**継承:** java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)  
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

プレゼンテーションで使用される色を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColorType()](#getColorType--) | 色定義方法を取得または設定します。 |
| [setColorType(int value)](#setColorType-int-) | 色定義方法を取得または設定します。 |
| [getColor()](#getColor--) | すべての色変換が適用された結果の色を取得します。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | すべての色変換が適用された結果の色を取得します。 |
| [getPresetColor()](#getPresetColor--) | カラープリセットを取得または設定します。 |
| [setPresetColor(int value)](#setPresetColor-int-) | カラープリセットを取得または設定します。 |
| [getSystemColor()](#getSystemColor--) | システム カラー テーブルで識別された色を取得または設定します。 |
| [setSystemColor(int value)](#setSystemColor-int-) | システム カラー テーブルで識別された色を取得または設定します。 |
| [getSchemeColor()](#getSchemeColor--) | カラースキームで識別された色を取得または設定します。 |
| [setSchemeColor(int value)](#setSchemeColor-int-) | カラースキームで識別された色を取得または設定します。 |
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
| [getLuminance()](#getLuminance--) | HSL 表現の輝度成分を取得または設定します。 |
| [setLuminance(float value)](#setLuminance-float-) | HSL 表現の輝度成分を取得または設定します。 |
| [getColorTransform()](#getColorTransform--) | 色に適用された色変換のコレクションを取得します。 |
| [toString(int format)](#toString-int-) | 現在のカラー形式を表す文字列を取得します。 |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | 「color」からカラー形式をコピーします。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトとの等価性をチェックします。 |
| [hashCode()](#hashCode--) | ハッシュコードを取得します。 |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

色定義方法を取得または設定します。読み書き可能 [ColorType](../../com.aspose.slides/colortype)。

**戻り値:**  
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

色定義方法を取得または設定します。読み書き可能 [ColorType](../../com.aspose.slides/colortype)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Integer getColor()
```

すべての色変換が適用された結果の色を取得します。RGB 色を設定し、すべての色変換をクリアします。読み書き可能 java.lang.Integer。

**戻り値:**  
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

すべての色変換が適用された結果の色を取得します。RGB 色を設定し、すべての色変換をクリアします。読み書き可能 java.lang.Integer。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

カラープリセットを取得または設定します。読み書き可能 [PresetColor](../../com.aspose.slides/presetcolor)。

**戻り値:**  
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

カラープリセットを取得または設定します。読み書き可能 [PresetColor](../../com.aspose.slides/presetcolor)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

システム カラー テーブルで識別された色を取得または設定します。読み書き可能 [SystemColor](../../com.aspose.slides/systemcolor)。

**戻り値:**  
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

システム カラー テーブルで識別された色を取得または設定します。読み書き可能 [SystemColor](../../com.aspose.slides/systemcolor)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

カラースキームで識別された色を取得または設定します。読み書き可能 [SchemeColor](../../com.aspose.slides/schemecolor)。

**戻り値:**  
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

カラースキームで識別された色を取得または設定します。読み書き可能 [SchemeColor](../../com.aspose.slides/schemecolor)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

赤成分を取得または設定します。すべての色変換は無視されます。読み書き可能 byte。

**戻り値:**  
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

赤成分を取得または設定します。すべての色変換は無視されます。読み書き可能 byte。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

緑成分を取得または設定します。すべての色変換は無視されます。

**戻り値:**  
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

緑成分を取得または設定します。すべての色変換は無視されます。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

青成分を取得または設定します。すべての色変換は無視されます。読み書き可能 byte。

**戻り値:**  
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

青成分を取得または設定します。すべての色変換は無視されます。読み書き可能 byte。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

赤成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**戻り値:**  
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

赤成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

緑成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**戻り値:**  
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

緑成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

青成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**戻り値:**  
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

青成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

HSL 表現の色相成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**戻り値:**  
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

HSL 表現の色相成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

HSL 表現の彩度成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**戻り値:**  
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

HSL 表現の彩度成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

HSL 表現の輝度成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**戻り値:**  
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

HSL 表現の輝度成分を取得または設定します。すべての色変換は無視されます。読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

色に適用された色変換のコレクションを取得します。読み取り専用 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)。

**戻り値:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

現在のカラー形式を表す文字列を取得します。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | int | カラー文字列形式のタイプ。 |

**戻り値:**  
java.lang.String - 現在のカラー形式を表す文字列。

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

「color」からカラー形式をコピーします。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定されたオブジェクトとの等価性をチェックします。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | オブジェクト。 |

**戻り値:**  
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

ハッシュコードを取得します。

**戻り値:**  
int - ハッシュコード。

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**  
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**戻り値:**  
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

親 IPresentationComponent を取得します。読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)