---
title: CellFormat
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: テーブルセルの書式を表します。
type: docs
url: /ja/com.aspose.slides/cellformat/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)  
```
public final class CellFormat extends PVIObject implements ICellFormat
```

テーブルセルの書式を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | セルの塗りつぶしプロパティ オブジェクトを返します。 |
| [getBorderLeft()](#getBorderLeft--) | 左側の罫線ラインプロパティ オブジェクトを返します。 |
| [getBorderTop()](#getBorderTop--) | 上側の罫線ラインプロパティ オブジェクトを返します。 |
| [getBorderRight()](#getBorderRight--) | 右側の罫線ラインプロパティ オブジェクトを返します。 |
| [getBorderBottom()](#getBorderBottom--) | 下側の罫線ラインプロパティ オブジェクトを返します。 |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | 左上から右下への対角線プロパティ オブジェクトを返します。 |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | 左下から右上への対角線プロパティ オブジェクトを返します。 |
| [getEffective()](#getEffective--) | 継承とテーブル スタイルが適用された有効なテーブルセル書式プロパティを取得します。 |
| [getTransparency()](#getTransparency--) | 塗りつぶし色の透明度を取得または設定します。 |
| [setTransparency(float value)](#setTransparency-float-) | 塗りつぶし色の透明度を取得または設定します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**  
long

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

セルの塗りつぶしプロパティ オブジェクトを返します。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

左側の罫線ラインプロパティ オブジェクトを返します。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

上側の罫線ラインプロパティ オブジェクトを返します。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

右側の罫線ラインプロパティ オブジェクトを返します。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

下側の罫線ラインプロパティ オブジェクトを返します。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

左上から右下への対角線プロパティ オブジェクトを返します。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

左下から右上への対角線プロパティ オブジェクトを返します。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

継承とテーブル スタイルが適用された有効なテーブルセル書式プロパティを取得します。

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).

### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

塗りつぶし色の透明度を取得または設定します。読み書き可能 float 。

**戻り値:**  
float

### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

塗りつぶし色の透明度を取得または設定します。読み書き可能 float 。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |