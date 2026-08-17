---
title: IDataLabel
second_title: Aspose.Slides の Java API リファレンス
description: シリーズのラベルを表します。
type: docs
url: /ja/com.aspose.slides/idatalabel/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

シリーズのラベルを表します。
## メソッド

| Method | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False はデータ ラベルが表示されないことを意味します (そのためすべての Show*-flags (ShowValue, ...) は false です)。 |
| [hide()](#hide--) | すべての Show*-flags (ShowValue, ...) を false に設定してデータ ラベルを非表示にします。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | データ ラベルの形式を返します。 |
| [getValueFromCell()](#getValueFromCell--) | ワークブック データ セルを取得または設定します。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | ワークブック データ セルを取得または設定します。 |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat 設定または TextFrameForOverriding.Text の値に基づいて実際のラベル テキストを返します。 |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False はデータ ラベルが表示されないことを意味します (そのためすべての Show*-flags (ShowValue, ...) は false です)。 読み取り専用 boolean.

--------------------

データ ラベルが表示されている場合は Hide() メソッドで非表示にできます。データ ラベルが表示されていない場合 (IsVisible が false) は、Show*-flags (ShowValue, ...) を true に設定して表示できます。

**戻り値:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

すべての Show*-flags (ShowValue, ...) を false に設定してデータ ラベルを非表示にします。この後 IsVisible は false になります。

--------------------

データ ラベルが表示されていない場合 (IsVisible が false) は、Show*-flags (ShowValue, ...) を true に設定して表示できます。

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

データ ラベルの形式を返します。読み取り専用 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**戻り値:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

ワークブック データ セルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

ワークブック データ セルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

DataLabelFormat 設定または TextFrameForOverriding.Text の値に基づいて実際のラベル テキストを返します。

**戻り値:**
java.lang.String - 実際のラベル テキスト文字列