---
title: ErrorBarsCustomValues
second_title: Aspose.Slides for Java API リファレンス
description: エラーバーの値を指定します。
type: docs
url: /ja/com.aspose.slides/errorbarscustomvalues/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)  
```
public class ErrorBarsCustomValues extends DomObject<ChartDataPoint> implements IErrorBarsCustomValues
```

エラーバーの値を指定します。この値は Error bars value type が Custom の場合にのみ使用されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getXMinus()](#getXMinus--) | 負方向のエラーバーの値を指定します。 |
| [getYMinus()](#getYMinus--) | 負方向のエラーバーの値を指定します。 |
| [getXPlus()](#getXPlus--) | 正方向のエラーバーの値を指定します。 |
| [getYPlus()](#getYPlus--) | 正方向のエラーバーの値を指定します。 |

### getXMinus() {#getXMinus--}
```
public final IDoubleChartValue getXMinus()
```

負方向のエラーバーの値を指定します。error bars value type が Custom であり、ErrorBarsXFormat が許可されている場合に使用可能です。それ以外の場合、このプロパティは null を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getYMinus() {#getYMinus--}
```
public final IDoubleChartValue getYMinus()
```

負方向のエラーバーの値を指定します。error bars value type が Custom であり、ErrorBarsYFormat が許可されている場合に使用可能です。それ以外の場合、このプロパティは null を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getXPlus() {#getXPlus--}
```
public final IDoubleChartValue getXPlus()
```

正方向のエラーバーの値を指定します。error bars value type が Custom であり、ErrorBarsXFormat が許可されている場合に使用可能です。それ以外の場合、このプロパティは null を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getYPlus() {#getYPlus--}
```
public final IDoubleChartValue getYPlus()
```

正方向のエラーバーの値を指定します。error bars value type が Custom であり、ErrorBarsYFormat が許可されている場合に使用可能です。それ以外の場合、このプロパティは null を返します。読み取り専用 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**戻り値:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)