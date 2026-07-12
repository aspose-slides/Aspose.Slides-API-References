---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table cell.
type: docs
url: /ja/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

テーブルセルの書式を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | セルの塗りつぶしプロパティ オブジェクトを返します。 |
| [getBorderLeft()](#getBorderLeft--) | 左境界線プロパティ オブジェクトを返します。 |
| [getBorderTop()](#getBorderTop--) | 上境界線プロパティ オブジェクトを返します。 |
| [getBorderRight()](#getBorderRight--) | 右境界線プロパティ オブジェクトを返します。 |
| [getBorderBottom()](#getBorderBottom--) | 下境界線プロパティ オブジェクトを返します。 |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | 左上から右下への対角線プロパティ オブジェクトを返します。 |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | 左下から右上への対角線プロパティ オブジェクトを返します。 |
| [getTransparency()](#getTransparency--) | 塗りつぶし色の透明度を取得または設定します。 |
| [setTransparency(float value)](#setTransparency-float-) | 塗りつぶし色の透明度を取得または設定します。 |
| [getEffective()](#getEffective--) | 継承およびテーブルスタイルが適用された、効果的なテーブルセル書式プロパティを取得します。 |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


セルの塗りつぶしプロパティ オブジェクトを返します。 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


左境界線プロパティ オブジェクトを返します。 読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


上境界線プロパティ オブジェクトを返します。 読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


右境界線プロパティ オブジェクトを返します。 読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


下境界線プロパティ オブジェクトを返します。 読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


左上から右下への対角線プロパティ オブジェクトを返します。 読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


左下から右上への対角線プロパティ オブジェクトを返します。 読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


塗りつぶし色の透明度を取得または設定します。 読み取り/書き込み  float .

**戻り値:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


塗りつぶし色の透明度を取得または設定します。 読み取り/書き込み  float .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


継承およびテーブルスタイルが適用された、効果的なテーブルセル書式プロパティを取得します。

**戻り値:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).