---  
title: IChartTextBlockFormat  
second_title: Aspose.Slides for Java API Reference  
description: チャートテキスト要素の書式設定プロパティを表します。  
type: docs  
url: /ja/com.aspose.slides/icharttextblockformat/  
---```
public interface IChartTextBlockFormat
```

チャートテキスト要素の書式設定プロパティを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | TextFrame の垂直アンカー テキストを取得または設定します。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame の垂直アンカー テキストを取得または設定します。 |
| [getCenterText()](#getCenterText--) | NullableBool.True の場合、テキストはボックス内で水平方向に中央揃えになるべきです。 |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True の場合、テキストはボックス内で水平方向に中央揃えになるべきです。 |
| [getTextVerticalType()](#getTextVerticalType--) | テキストの向きを決定します。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | テキストの向きを決定します。 |
| [getMarginLeft()](#getMarginLeft--) | TextFrame の左余白（ポイント）を取得または設定します。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame の左余白（ポイント）を取得または設定します。 |
| [getMarginRight()](#getMarginRight--) | TextFrame の右余白（ポイント）を取得または設定します。 |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame の右余白（ポイント）を取得または設定します。 |
| [getMarginTop()](#getMarginTop--) | TextFrame の上余白（ポイント）を取得または設定します。 |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame の上余白（ポイント）を取得または設定します。 |
| [getMarginBottom()](#getMarginBottom--) | TextFrame の下余白（ポイント）を取得または設定します。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame の下余白（ポイント）を取得または設定します。 |
| [getWrapText()](#getWrapText--) | TextFrame の余白でテキストが折り返される場合は true です。 |
| [setWrapText(byte value)](#setWrapText-byte-) | TextFrame の余白でテキストが折り返される場合は true です。 |
| [getAutofitType()](#getAutofitType--) | テキストの自動調整モードを取得または設定します。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | テキストの自動調整モードを取得または設定します。 |
| [getRotationAngle()](#getRotationAngle--) | バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。 |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

TextFrame の垂直アンカー テキストを取得または設定します。読み取り/書き込み [TextAnchorType](../../com.aspose.slides/textanchortype)。

**戻り値:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

TextFrame の垂直アンカー テキストを取得または設定します。読み取り/書き込み [TextAnchorType](../../com.aspose.slides/textanchortype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

NullableBool.True の場合、テキストはボックス内で水平方向に中央揃えになるべきです。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True の場合、テキストはボックス内で水平方向に中央揃えになるべきです。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

テキストの向きを決定します。プロパティ RotationAngle のカスタム角度と合わせた視覚的テキスト回転の結果値です。読み取り/書き込み [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**戻り値:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

テキストの向きを決定します。プロパティ RotationAngle のカスタム角度と合わせた視覚的テキスト回転の結果値です。読み取り/書き込み [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

TextFrame の左余白（ポイント）を取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み double。

**戻り値:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

TextFrame の左余白（ポイント）を取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

TextFrame の右余白（ポイント）を取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み double。

**戻り値:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

TextFrame の右余白（ポイント）を取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

TextFrame の上余白（ポイント）を取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み double。

**戻り値:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

TextFrame の上余白（ポイント）を取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

TextFrame の下余白（ポイント）を取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み double。

**戻り値:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

TextFrame の下余白（ポイント）を取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

TextFrame の余白でテキストが折り返される場合は true です。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2007/2013 で完全にサポート）。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

TextFrame の余白でテキストが折り返される場合は true です。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2007/2013 で完全にサポート）。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

テキストの自動調整モードを取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み [TextAutofitType](../../com.aspose.slides/textautofittype)。

**戻り値:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

テキストの自動調整モードを取得または設定します。このプロパティの変更は、DataLabel および DataLabelFormat というチャートパーツにのみ影響を与える可能性があります（PowerPoint 2013 で完全にサポート、PowerPoint 2007 では描画に影響なし）。読み取り/書き込み [TextAutofitType](../../com.aspose.slides/textautofittype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、関連付けられたシェイプの回転が使用されます。指定されている場合、シェイプから独立して適用されます。つまり、シェイプに回転が適用されているだけでなく、テキスト自体にも回転が適用される可能性があります。プロパティ TextVerticalType の事前定義された垂直タイプと合わせた視覚的テキスト回転の結果値です。読み取り/書き込み float。

--------------------

> ```
> 形状に 90 度の時計回りの回転が適用されているケースを考えてみてください。 
>  さらに、テキスト本体自体にも -90 度の反時計回りの回転が適用されています。 
>  その結果、形状は回転しているように見えますが、その中のテキストはまったく回転していないかのように見えます。
> ```


**戻り値:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、関連付けられたシェイプの回転が使用されます。指定されている場合、シェイプから独立して適用されます。つまり、シェイプに回転が適用されているだけでなく、テキスト自体にも回転が適用される可能性があります。プロパティ TextVerticalType の事前定義された垂直タイプと合わせた視覚的テキスト回転の結果値です。読み取り/書き込み float。

--------------------

> ```
> 形状に時計回りに 90 度の回転が適用されているケースを考えてみてください。 
>  さらに、テキスト本体自体にも -90 度の反時計回りの回転が適用されています。 
>  反時計回りに適用されます。その結果、形状は回転しているように見えますが 
>  回転しているように見えますが、その中のテキストはまったく回転していないかのように見えます。
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |