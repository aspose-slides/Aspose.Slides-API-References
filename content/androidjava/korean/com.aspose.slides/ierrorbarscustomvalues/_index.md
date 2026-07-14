---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Android via Java API Reference
description: 오류 막대 값을 지정합니다.
type: docs
url: /ko/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

오류 막대 값을 지정합니다. 오류 막대 값 유형이 Custom인 경우에만 사용해야 합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getXMinus()](#getXMinus--) | Specifies the error bar value in the negative direction. |
| [getYMinus()](#getYMinus--) | Specifies the error bar value in the negative direction. |
| [getXPlus()](#getXPlus--) | Specifies the error bar value in the positive direction. |
| [getYPlus()](#getYPlus--) | Specifies the error bar value in the positive direction. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

오류 막대 값을 음수 방향으로 지정합니다. 오류 막대 값 유형이 Custom이고 ErrorBarsXFormat이 허용되는 경우에 사용할 수 있습니다. 다른 경우 이 속성은 null을 반환합니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

오류 막대 값을 음수 방향으로 지정합니다. 오류 막대 값 유형이 Custom이고 ErrorBarsYFormat이 허용되는 경우에 사용할 수 있습니다. 다른 경우 이 속성은 null을 반환합니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

오류 막대 값을 양수 방향으로 지정합니다. 오류 막대 값 유형이 Custom이고 ErrorBarsXFormat이 허용되는 경우에 사용할 수 있습니다. 다른 경우 이 속성은 null을 반환합니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

오류 막대 값을 양수 방향으로 지정합니다. 오류 막대 값 유형이 Custom이고 ErrorBarsYFormat이 허용되는 경우에 사용할 수 있습니다. 다른 경우 이 속성은 null을 반환합니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)