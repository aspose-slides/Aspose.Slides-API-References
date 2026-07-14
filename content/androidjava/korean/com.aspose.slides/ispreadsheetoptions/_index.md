---
title: ISpreadsheetOptions
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 추가 스프레드시트 동작을 지정하는 데 사용할 수 있는 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

추가 스프레드시트 동작을 지정하는 데 사용할 수 있는 옵션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | 이중 바이트 문자 집합(DBCS)을 사용하는 언어용 함수 계산에 사용할 선호 문화권 정보를 가져오거나 설정합니다. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | 이중 바이트 문자 집합(DBCS)을 사용하는 언어용 함수 계산에 사용할 선호 문화권 정보를 가져오거나 설정합니다. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | 차트의 데이터 소스가 외부 워크북이며 사용할 수 없는 경우 차트 캐시에서 복구됩니다. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | 차트의 데이터 소스가 외부 워크북이며 사용할 수 없는 경우 차트 캐시에서 복구됩니다. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


이중 바이트 문자 집합(DBCS)을 사용하는 언어용 함수 계산에 사용할 선호 문화권 정보를 가져오거나 설정합니다.

**반환값:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


이중 바이트 문자 집합(DBCS)을 사용하는 언어용 함수 계산에 사용할 선호 문화권 정보를 가져오거나 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


차트의 데이터 소스가 외부 워크북이며 사용할 수 없는 경우 차트 캐시에서 복구됩니다.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> 
```

**반환값:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


차트의 데이터 소스가 외부 워크북이며 사용할 수 없는 경우 차트 캐시에서 복구됩니다.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |