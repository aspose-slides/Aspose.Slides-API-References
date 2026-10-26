---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Represents chart categories.
type: docs
url: /ja/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

チャートカテゴリを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getUseCell()](#getUseCell--) | true の場合、AsCell プロパティが実際の値です。 |
| [getAsCell()](#getAsCell--) | IChartDataCell オブジェクトを取得または設定します。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell オブジェクトを取得または設定します。 |
| [getAsLiteral()](#getAsLiteral--) | UseCell が false の場合、AsLiteral を取得または設定します。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | UseCell が false の場合、AsLiteral を取得または設定します。 |
| [getValue()](#getValue--) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。 |
| [getGroupingLevels()](#getGroupingLevels--) | チャートカテゴリのグルーピング レベルの値を管理するコンテナです。 |
| [remove()](#remove--) | カテゴリをチャートから削除します。 |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

true の場合、AsCell プロパティが実際の値です。つまり、ワークシートがカテゴリの保存に使用されます（この場合、複数レベルのカテゴリをサポートします）。false の場合、AsLiteral プロパティが実際の値です。つまり、ワークシートはカテゴリの保存に使用されません（この場合、複数レベルのカテゴリはサポートされません）。読み取り専用の boolean です。

--------------------

このプロパティの値を変更するには（コレクション内のすべてのカテゴリに対して）[ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) プロパティに新しい値を設定してください。

**戻り値:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

IChartDataCell オブジェクトを取得または設定します。カテゴリがマルチレベルの場合、レベル "0" の IChartDataCell オブジェクトが使用されます。読み書き可能な [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

IChartDataCell オブジェクトを取得または設定します。カテゴリがマルチレベルの場合、レベル "0" の IChartDataCell オブジェクトが使用されます。読み書き可能な [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

UseCell が false の場合、AsLiteral を取得または設定します。読み書き可能な Object。

**戻り値:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

UseCell が false の場合、AsLiteral を取得または設定します。読み書き可能な Object。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。読み書き可能な Object。

**戻り値:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。読み書き可能な Object。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

チャートカテゴリのグルーピング レベルの値を管理するコンテナです。マルチレベルカテゴリは 1 つ以上のグルーピング レベルを含みます。グルーピング レベルのインデックスは 0 から始まります。読み取り専用の [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**戻り値:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

カテゴリをチャートから削除します。