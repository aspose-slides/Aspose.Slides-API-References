---
title: RowFormat
second_title: Aspose.Slides の Java API リファレンス
description: テーブル行の書式を表します。
type: docs
url: /ja/com.aspose.slides/rowformat/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject  
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

テーブル行の書式を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承およびテーブル スタイルが適用された有効なテーブル行の書式プロパティを取得します。 |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```

継承およびテーブル スタイルが適用された有効なテーブル行の書式プロパティを取得します。

--------------------

> ```
> この例では、異なるテーブルロジック部分の有効な塗りつぶし形式の取得方法を示します。
>  セルの書式設定は常に行の書式設定よりも優先され、行は列よりも優先され、列はテーブル全体よりも優先されることに注意してください。
>  したがって、最終的に CellFormatEffectiveData のプロパティが常にテーブルの描画に使用されます。以下のコードは API の例です。
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata)。

### getVersion() {#getVersion--}
```
public final long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

親 IPresentationComponent を返します。読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)