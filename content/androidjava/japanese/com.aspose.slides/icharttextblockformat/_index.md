---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android の Java API リファレンス
description: チャートのテキスト要素の書式設定プロパティを表します。
type: docs
url: /ja/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

チャートのテキスト要素の書式設定プロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | TextFrame の垂直アンカー テキストを取得または設定します。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame の垂直アンカー テキストを取得または設定します。 |
| [getCenterText()](#getCenterText--) | NullableBool.True の場合、テキストはボックス内で水平方向に中央揃えにする必要があります。 |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True の場合、テキストはボックス内で水平方向に中央揃えにする必要があります。 |
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
| [getWrapText()](#getWrapText--) | TextFrame の余白でテキストが折り返されている場合は true です。 |
| [setWrapText(byte value)](#setWrapText-byte-) | TextFrame の余白でテキストが折り返されている場合は true です。 |
| [getAutofitType()](#getAutofitType--) | テキストの自動調整モードを取得または設定します。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | テキストの自動調整モードを取得または設定します。 |
| [getRotationAngle()](#getRotationAngle--) | バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。 |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

TextFrame の垂直アンカー テキストを取得または設定します。 読み取り/書き込み [TextAnchorType](../../com.aspose.slides/textanchortype).

**戻り値:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

TextFrame の垂直アンカー テキストを取得または設定します。 読み取り/書き込み [TextAnchorType](../../com.aspose.slides/textanchortype).

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

NullableBool.True の場合、テキストはボックス内で水平方向に中央揃えにする必要があります。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True の場合、テキストはボックス内で水平方向に中央揃えにする必要があります。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

テキストの向きを決定します。このプロパティとプロパティ RotationAngle のカスタム角度から要約された視覚的テキスト回転の結果値です。 読み取り/書き込み [TextVerticalType](../../com.aspose.slides/textverticaltype).

**戻り値:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

テキストの向きを決定します。このプロパティとプロパティ RotationAngle のカスタム角度から要約された視覚的テキスト回転の結果値です。 読み取り/書き込み [TextVerticalType](../../com.aspose.slides/textverticaltype).

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

TextFrame の左余白（ポイント）を取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み double.

**戻り値:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

TextFrame の左余白（ポイント）を取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み double.

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

TextFrame の右余白（ポイント）を取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み double.

**戻り値:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

TextFrame の右余白（ポイント）を取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み double.

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

TextFrame の上余白（ポイント）を取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み double.

**戻り値:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

TextFrame の上余白（ポイント）を取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み double.

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

TextFrame の下余白（ポイント）を取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み double.

**戻り値:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

TextFrame の下余白（ポイント）を取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み double.

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

TextFrame の余白でテキストが折り返されている場合は true です。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2007/2013 で完全にサポート）。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

TextFrame の余白でテキストが折り返されている場合は true です。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2007/2013 で完全にサポート）。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

テキストの自動調整モードを取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み [TextAutofitType](../../com.aspose.slides/textautofittype).

**戻り値:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

テキストの自動調整モードを取得または設定します。このプロパティの変更は、次のチャート パーツにのみ影響を与える可能性があります：DataLabel と DataLabelFormat（PowerPoint 2013 で完全にサポート; PowerPoint 2007 ではレンダリングに影響なし）。 読み取り/書き込み [TextAutofitType](../../com.aspose.slides/textautofittype).

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、添付シェイプの回転が使用されます。指定されている場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されると同時に、テキスト自体にも回転が適用されます。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。 読み取り/書き込み float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**戻り値:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、添付シェイプの回転が使用されます。指定されている場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されると同時に、テキスト自体にも回転が適用されます。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。 読み取り/書き込み float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | float |  |