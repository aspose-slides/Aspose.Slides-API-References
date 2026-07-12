---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: チャートのカテゴリを表します。
type: docs
url: /ja/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

チャートのカテゴリを表します。
## Methods

| メソッド | 説明 |
| --- | --- |
| [getUseCell()](#getUseCell--) | true の場合、AsCell プロパティが実際のものになります。 |
| [getAsCell()](#getAsCell--) | IChartDataCell オブジェクトを取得または設定します。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell オブジェクトを取得または設定します。 |
| [getAsLiteral()](#getAsLiteral--) | UseCell が false の場合、AsLiteral を取得または設定します。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | UseCell が false の場合、AsLiteral を取得または設定します。 |
| [getValue()](#getValue--) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。 |
| [getGroupingLevels()](#getGroupingLevels--) | チャートカテゴリのグループ化レベルの値を管理するコンテナです。 |
| [remove()](#remove--) | チャートからカテゴリを削除します。 |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

true の場合、AsCell プロパティが実際のものになります。言い換えると、ワークシートがカテゴリの保存に使用されます（このケースは複数レベルのカテゴリをサポートします）。false の場合、AsLiteral プロパティが実際のものになります。言い換えると、ワークシートはカテゴリの保存に使用されません（このケースは複数レベルのカテゴリをサポートしません）。読み取り専用の boolean。

このプロパティの値を変更するには（コレクション内のすべてのカテゴリに対して）[ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) プロパティに新しい値を設定します。

**戻り値:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

IChartDataCell オブジェクトを取得または設定します。カテゴリが複数レベルの場合、レベル "0" の IChartDataCell オブジェクトが使用されます。読み取り/書き込み [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

IChartDataCell オブジェクトを取得または設定します。カテゴリが複数レベルの場合、レベル "0" の IChartDataCell オブジェクトが使用されます。読み取り/書き込み [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

UseCell が false の場合、AsLiteral を取得または設定します。読み取り/書き込み Object。

**戻り値:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

UseCell が false の場合、AsLiteral を取得または設定します。読み取り/書き込み Object。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。読み取り/書き込み Object。

**戻り値:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。読み取り/書き込み Object。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

チャートカテゴリのグループ化レベルの値を管理するコンテナです。マルチレベルカテゴリは複数のグループ化レベルを含みます。グループ化レベルのインデックスはゼロベースです。読み取り専用 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**戻り値:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

チャートからカテゴリを削除します。