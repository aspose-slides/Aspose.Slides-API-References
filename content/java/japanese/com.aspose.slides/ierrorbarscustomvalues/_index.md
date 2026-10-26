---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Java API Reference
description: Specifies the errors bar values.
type: docs
url: /ja/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

エラーバーの値を指定します。Error bars の値タイプが Custom の場合にのみ使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getXMinus()](#getXMinus--) | 負の方向のエラーバーの値を指定します。 |
| [getYMinus()](#getYMinus--) | 負の方向のエラーバーの値を指定します。 |
| [getXPlus()](#getXPlus--) | 正の方向のエラーバーの値を指定します。 |
| [getYPlus()](#getYPlus--) | 正の方向のエラーバーの値を指定します。 |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```


負の方向のエラーバーの値を指定します。エラーバーの値タイプが Custom であり、ErrorBarsXFormat が許可されている場合に利用可能です。その他の場合、このプロパティは null を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```


負の方向のエラーバーの値を指定します。エラーバーの値タイプが Custom であり、ErrorBarsYFormat が許可されている場合に利用可能です。その他の場合、このプロパティは null を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```


正の方向のエラーバーの値を指定します。エラーバーの値タイプが Custom であり、ErrorBarsXFormat が許可されている場合に利用可能です。その他の場合、このプロパティは null を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```


正の方向のエラーバーの値を指定します。エラーバーの値タイプが Custom であり、ErrorBarsYFormat が許可されている場合に利用可能です。その他の場合、このプロパティは null を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)