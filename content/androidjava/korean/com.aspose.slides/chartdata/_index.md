---
title: ChartData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 차트 그리기에 사용되는 데이터를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartdata/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)  
```
public class ChartData extends DomObject<Chart> implements IChartData
```

차트 그리기에 사용되는 데이터를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 차트 시리즈 또는 카테고리에 사용되는 셀을 생성하는 셀 공장을 가져옵니다. |
| [getSeries()](#getSeries--) | 시리즈를 가져옵니다. |
| [getSeriesGroups()](#getSeriesGroups--) | 시리즈 그룹을 가져옵니다. |
| [getCategories()](#getCategories--) | 주 카테고리를 가져옵니다(또는 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 속성이 false인 경우 기본 및 보조 카테고리를 모두 가져옵니다). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | false일 경우 \#getSecondaryCategories.getSecondaryCategories 속성이 null을 반환하고 \#getCategories.getCategories 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | false일 경우 \#getSecondaryCategories.getSecondaryCategories 속성이 null을 반환하고 \#getCategories.getCategories 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. |
| [getSecondaryCategories()](#getSecondaryCategories--) | \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 속성이 true인 경우 보조 카테고리를 가져옵니다. |
| [readWorkbookStream()](#readWorkbookStream--) | 내부에 포함된 Excel 워크북을 메모리 스트림에 씁니다. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 내부에 포함된 Excel 워크북을 사용자가 지정한 값으로 초기화합니다. |
| [getDataSourceType()](#getDataSourceType--) | 외부 데이터 소스인 경우 외부 워크북 경로를 나타내며, 그렇지 않으면 null입니다. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 차트의 데이터 소스를 나타냅니다. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 내장 워크북의 유형을 가져옵니다. |
| [getRange()](#getRange--) | 차트 데이터 범위를 가져옵니다. |
| [setRange(String formula)](#setRange-java.lang.String-) | 차트 데이터 범위를 설정합니다. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 외부 워크북을 차트의 데이터 소스로 설정합니다. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 외부 워크북을 차트의 데이터 소스로 설정합니다. |
| [switchRowColumn()](#switchRowColumn--) | 축을 따라 데이터를 전환합니다. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

차트 시리즈 또는 카테고리에 사용되는 셀을 생성하는 셀 공장을 가져옵니다. 읽기 전용 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**반환값:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

시리즈를 가져옵니다. 읽기 전용 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**반환값:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

시리즈 그룹을 가져옵니다. 읽기 전용 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) 각 시리즈 그룹은 결합 가능한 타입을 가진 시리즈를 포함합니다. 결합 가능한 시리즈 타입 그룹은 CombinableSeriesTypesGroup 열거형으로 정의되고 설명됩니다. 또한 각 시리즈 그룹은 기본 축에 플롯되는 시리즈 또는 보조 축에 플롯되는 시리즈를 포함합니다(하나의 그룹에 두 경우가 모두 포함되지 않음). 따라서 시리즈 그룹화 원칙은 앞에서 언급한 타입 그룹 및 기본/보조 플롯 타입에 따라 그룹화하는 것입니다.

**반환값:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

주 카테고리를 가져옵니다(또는 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 속성이 false인 경우 기본 및 보조 카테고리를 모두 가져옵니다). 읽기 전용 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 관련 카테고리는 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 관련 카테고리는 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

속성이 false이면 (\#getSecondaryCategories.getSecondaryCategories) 속성이 null을 반환하고 이 \#getCategories.getCategories 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. 속성이 true이면 (\#getSecondaryCategories.getSecondaryCategories) 속성의 데이터가 보조 시리즈에 사용되고 이 \#getCategories.getCategories 속성의 데이터가 기본 시리즈에 사용됩니다.

**반환값:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

false이면 \#getSecondaryCategories.getSecondaryCategories 속성이 null을 반환하고 \#getCategories.getCategories 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true이면 \#getSecondaryCategories.getSecondaryCategories 속성의 데이터가 보조 시리즈에 사용되고 \#getCategories.getCategories 속성의 데이터가 기본 시리즈에 사용됩니다. 읽기/쓰기 boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 관련 카테고리는 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 관련 카테고리는 series.getChart().getChartData().getCategories()
>  }
> ```

**반환값:**  
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

false이면 \#getSecondaryCategories.getSecondaryCategories 속성이 null을 반환하고 \#getCategories.getCategories 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true이면 \#getSecondaryCategories.getSecondaryCategories 속성의 데이터가 보조 시리즈에 사용되고 \#getCategories.getCategories 속성의 데이터가 기본 시리즈에 사용됩니다. 읽기/쓰기 boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 관련 카테고리는 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 관련 카테고리는 series.getChart().getChartData().getCategories()
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 속성이 true인 경우 보조 카테고리를 가져옵니다. 읽기 전용 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 관련 카테고리는 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 관련 카테고리는 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

속성이 false이면 이 (\#getSecondaryCategories.getSecondaryCategories) 속성이 null을 반환하고 \#getCategories.getCategories 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. 속성이 true이면 이 \#getSecondaryCategories.getSecondaryCategories 속성의 데이터가 보조 시리즈에 사용되고 \#getCategories.getCategories 속성의 데이터가 기본 시리즈에 사용됩니다.

**반환값:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

내부에 포함된 Excel 워크북을 메모리 스트림에 씁니다.

**반환값:**  
byte[] - 내부에 포함된 Excel 워크북의 복사본을 포함하는 바이트 배열 인스턴스를 반환합니다.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

내부에 포함된 Excel 워크북을 사용자가 지정한 값으로 초기화합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ms | byte[] | 전체 Excel 워크북을 포함하는 사용자가 제공한 스트림. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

외부 데이터 소스인 경우 외부 워크북 경로를 나타내며, 그렇지 않으면 null입니다.

**반환값:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

차트의 데이터 소스를 나타냅니다.

**반환값:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

내장 워크북의 유형을 가져옵니다. DataSourceType (\#getDataSourceType.getDataSourceType) 가 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)인 경우 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)을 반환합니다. 읽기 전용 [WorkbookType](../../com.aspose.slides/workbooktype).

**반환값:**  
int

### getRange() {#getRange--}
```
public final String getRange()
```

차트 데이터 범위를 가져옵니다.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**반환값:**  
java.lang.String - 셀 데이터 범위 수식입니다. 예: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

차트 데이터 범위를 설정합니다. 새 데이터 범위에 따라 시리즈와 카테고리가 업데이트됩니다. 데이터 범위의 시리즈 수가 차트 데이터의 시리즈 수보다 많으면 현재 컬렉션의 마지막 시리즈와 동일한 유형의 추가 시리즈가 컬렉션 끝에 추가됩니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formula | java.lang.String | 셀 데이터 범위 수식입니다. 예: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

외부 워크북을 차트의 데이터 소스로 설정합니다. 차트 데이터가 대상 워크북에서 업데이트됩니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>     if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| workbookPath | java.lang.String | 대상 워크북의 경로 |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

외부 워크북을 차트의 데이터 소스로 설정합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| workbookPath | java.lang.String | 대상 워크북의 경로 |
| updateChartData | boolean | 값이 false이면 워크북 경로만 업데이트됩니다. 차트 데이터는 대상 워크북에서 로드되고 업데이트되지 않습니다. 대상 워크북이 없거나 사용할 수 없을 때 사용할 수 있습니다. 값이 true이면 차트 데이터가 대상 워크북에서 업데이트됩니다. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

축을 따라 데이터를 전환합니다. X축에 차트된 데이터가 Y축으로 이동하고 그 반대도 마찬가지입니다.