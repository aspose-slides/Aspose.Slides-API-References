---
title: TableFormat
second_title: Aspose.Slides for Android の Java API リファレンス
description: テーブルの書式を表します。
type: docs
url: /ja/com.aspose.slides/tableformat/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject  
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

テーブルの書式を表します。
## Methods

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | テーブル塗りつぶしプロパティ オブジェクトを返します。 |
| [getTransparency()](#getTransparency--) | 塗りつぶし色の透明度を取得または設定します。 |
| [setTransparency(float value)](#setTransparency-float-) | 塗りつぶし色の透明度を取得または設定します。 |
| [getEffective()](#getEffective--) | 継承とテーブル スタイルが適用された有効なテーブル書式プロパティを取得します。 |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

テーブル塗りつぶしプロパティ オブジェクトを返します。 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat).

**戻り値:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

塗りつぶし色の透明度を取得または設定します。 読み書き  float .

**戻り値:**  
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

塗りつぶし色の透明度を取得または設定します。 読み書き  float .

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

継承とテーブル スタイルが適用された有効なテーブル書式プロパティを取得します。

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

バージョン。 読み取り専用 long.

**戻り値:**  
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

親 IPresentationComponent を返します。 読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**戻り値:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)