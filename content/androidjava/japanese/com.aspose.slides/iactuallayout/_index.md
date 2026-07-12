---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /ja/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

チャート要素の実際の位置を指定します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getActualX()](#getActualX--) | チャートの左上隅を基準として、チャート要素の実際の x 位置（左）を指定します。 |
| [getActualY()](#getActualY--) | チャートの左上隅を基準として、チャート要素の実際の上位置を指定します。 |
| [getActualWidth()](#getActualWidth--) | チャート要素の実際の幅を指定します。 |
| [getActualHeight()](#getActualHeight--) | チャート要素の実際の高さを指定します。 |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

チャートの左上隅を基準として、チャート要素の実際の x 位置（左）を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。float を読み取ります。

**戻り値:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

チャートの左上隅を基準として、チャート要素の実際の上位置を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。float を読み取ります。

**戻り値:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

チャート要素の実際の幅を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。float を読み取ります。

**戻り値:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

チャート要素の実際の高さを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。float を読み取ります。

**戻り値:**
float