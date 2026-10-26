---
title: RowFormat
second_title: Java API リファレンスによる Android 向け Aspose.Slides
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
| [getEffective()](#getEffective--) | 継承とテーブルスタイルが適用された有効なテーブル行書式プロパティを取得します。 |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```

継承とテーブルスタイルが適用された有効なテーブル行書式プロパティを取得します。

--------------------

> ```
> この例では、異なるテーブルロジック部分に対して有効な塗りつぶしフォーマットを取得する方法を示しています。
>  セルの書式設定は常に行の書式設定よりも優先度が高く、行は列よりも、列はテーブル全体よりも優先されることに注意してください。
>  最終的にテーブルの描画には常に CellFormatEffectiveData のプロパティが使用されます。以下のコードは API の例示にすぎません。
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
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - A [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).

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