---
title: ChartCategory
second_title: Aspose.Slides の Java API リファレンス
description: チャートカテゴリを表します。
type: docs
url: /ja/com.aspose.slides/chartcategory/
---
**継承:**  
java.lang.Object

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject  
```
public class ChartCategory implements IChartCategory, IDOMObject
```

チャートのカテゴリを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getUseCell()](#getUseCell--) | true の場合、AsCell プロパティが実際の値になります。 |
| [getAsCell()](#getAsCell--) | IChartDataCell オブジェクトを取得または設定します。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell オブジェクトを取得または設定します。 |
| [getAsLiteral()](#getAsLiteral--) | AsLiteral オブジェクトを取得または設定します。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | AsLiteral オブジェクトを取得または設定します。 |
| [getValue()](#getValue--) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。 |
| [getGroupingLevels()](#getGroupingLevels--) | チャートカテゴリのグループ化レベルの値を管理するコンテナです。 |
| [getCachedValue()](#getCachedValue--) | チャートカテゴリのキャッシュされた値を取得します。 |
| [remove()](#remove--) | カテゴリをチャートから削除します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

true の場合、AsCell プロパティが実際の値になります。言い換えれば、ワークシートはカテゴリの保存に使用されます（この場合、複数レベルのカテゴリをサポートします）。false の場合、AsLiteral プロパティが実際の値になります。言い換えれば、ワークシートはカテゴリの保存に使用されません（この場合、複数レベルのカテゴリはサポートされません）。読み取り専用 boolean。

--------------------

このプロパティの値を変更するには（コレクション内のすべてのカテゴリに対して）ChartCategoryCollection.UseCells プロパティに新しい値を設定します。

**戻り値:**  
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

IChartDataCell オブジェクトを取得または設定します。カテゴリが複数レベルの場合、レベル "0" 用の IChartDataCell オブジェクトが使用されます。読み書き可能 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**戻り値:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

IChartDataCell オブジェクトを取得または設定します。カテゴリが複数レベルの場合、レベル "0" 用の IChartDataCell オブジェクトが使用されます。読み書き可能 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

AsLiteral オブジェクトを取得または設定します。読み書き可能 Object。

**戻り値:**  
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

AsLiteral オブジェクトを取得または設定します。読み書き可能 Object。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。読み書き可能 Object。

**戻り値:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。読み書き可能 Object。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

チャートカテゴリのグループ化レベルの値を管理するコンテナです。複数レベルのカテゴリは 1 つ以上のグループ化レベルを含みます。グループ化レベルのインデックスは 0 から始まります。読み取り専用 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**戻り値:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

チャートカテゴリのキャッシュされた値を取得します。読み取り専用 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // すべてのキャッシュされたチャートカテゴリの値を出力します。
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```

**戻り値:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### remove() {#remove--}
```
public final void remove()
```

カテゴリをチャートから削除します。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを取得します。読み取り専用 IDOMObject。

**戻り値:**  
com.aspose.slides.IDOMObject