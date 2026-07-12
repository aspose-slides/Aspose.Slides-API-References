---
title: ChartCategory
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: チャートカテゴリを表します。
type: docs
url: /ja/com.aspose.slides/chartcategory/
---
**継承:**
java.lang.Object

**実装されたインターフェイス:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

チャートカテゴリを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getUseCell()](#getUseCell--) | true の場合、AsCell プロパティが有効です。 |
| [getAsCell()](#getAsCell--) | IChartDataCell オブジェクトを取得または設定します。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell オブジェクトを取得または設定します。 |
| [getAsLiteral()](#getAsLiteral--) | AsLiteral オブジェクトを取得または設定します。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | AsLiteral オブジェクトを取得または設定します。 |
| [getValue()](#getValue--) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。 |
| [getGroupingLevels()](#getGroupingLevels--) | チャートカテゴリのグルーピングレベルの値を管理するコンテナです。 |
| [remove()](#remove--) | カテゴリをチャートから削除します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

true の場合、AsCell プロパティが有効です。つまり、ワークシートはカテゴリの保存に使用されます（このケースは多層カテゴリをサポートします）。false の場合、AsLiteral プロパティが有効です。つまり、ワークシートはカテゴリの保存に使用されません（このケースは多層カテゴリをサポートしません）。読み取り専用 boolean。

--------------------

このプロパティの値を変更するには（コレクション内のすべてのカテゴリに対して）、ChartCategoryCollection.UseCells プロパティに新しい値を設定します。

**戻り値:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

IChartDataCell オブジェクトを取得または設定します。カテゴリが多層の場合、レベル "0" の IChartDataCell オブジェクトが使用されます。読み書き [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

IChartDataCell オブジェクトを取得または設定します。カテゴリが多層の場合、レベル "0" の IChartDataCell オブジェクトが使用されます。読み書き [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

AsLiteral オブジェクトを取得または設定します。読み書き Object。

**戻り値:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

AsLiteral オブジェクトを取得または設定します。読み書き Object。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。読み書き Object。

**戻り値:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。読み書き Object。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

チャートカテゴリのグルーピングレベルの値を管理するコンテナです。多層カテゴリは複数のグルーピングレベルを含みます。グルーピングレベルのインデックスはゼロベースです。読み取り専用 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**戻り値:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
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