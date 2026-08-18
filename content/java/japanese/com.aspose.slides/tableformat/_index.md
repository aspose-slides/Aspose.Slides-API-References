---
title: TableFormat
second_title: Aspose.Slides for Java API リファレンス
description: テーブルのフォーマットを表します。
type: docs
url: /ja/com.aspose.slides/tableformat/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

テーブルのフォーマットを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | テーブル塗りつぶしプロパティオブジェクトを返します。 |
| [getTransparency()](#getTransparency--) | 塗りつぶし色の透明度を取得または設定します。 |
| [setTransparency(float value)](#setTransparency-float-) | 塗りつぶし色の透明度を取得または設定します。 |
| [getEffective()](#getEffective--) | 継承とテーブルスタイルが適用された有効なテーブル書式設定プロパティを取得します。 |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

テーブル塗りつぶしプロパティオブジェクトを返します。 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat).

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

塗りつぶし色の透明度を取得または設定します。 読み書き可能  float 。

**戻り値:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

塗りつぶし色の透明度を取得または設定します。 読み書き可能  float 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

継承とテーブルスタイルが適用された有効なテーブル書式設定プロパティを取得します。

--------------------

> ```
> この例は、テーブルのさまざまなロジック部分の有効な塗りつぶし形式を取得する方法を示します。
> セルの書式設定は常に行の書式設定よりも優先度が高く、行は列よりも、列はテーブル全体よりも優先されます。
> したがって最終的に CellFormatEffectiveData プロパティがテーブルの描画に常に使用されます。以下のコードは API の例です。
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
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata)。
### getVersion() {#getVersion--}
```
public final long getVersion()
```

バージョン。 読み取り専用 long。

**戻り値:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

IPresentationComponent の親を返します。 読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)