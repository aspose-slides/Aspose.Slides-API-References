---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: 차트 플로팅에 사용되는 데이터를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

차트 플로팅에 사용되는 데이터를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 차트 시리즈 또는 범주에 사용되는 셀을 생성하는 셀 팩토리를 가져옵니다. |
| [getSeries()](#getSeries--) | 시리즈를 가져옵니다. |
| [getSeriesGroups()](#getSeriesGroups--) | 시리즈 그룹을 가져옵니다. |
| [getCategories()](#getCategories--) | (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 속성이 false인 경우 기본 및 보조 범주를 모두 가져옵니다. |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | false이면 (\#getSecondaryCategories.getSecondaryCategories) 속성이 null을 반환하고 (\#getCategories.getCategories) 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | false이면 (\#getSecondaryCategories.getSecondaryCategories) 속성이 null을 반환하고 (\#getCategories.getCategories) 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. |
| [getSecondaryCategories()](#getSecondaryCategories--) | (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 속성이 true인 경우 보조 범주를 가져옵니다. |
| [readWorkbookStream()](#readWorkbookStream--) | 내부에 포함된 Excel 워크북을 메모리 스트림에 씁니다. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 내부에 포함된 Excel 워크북을 사용자가 지정한 값으로 초기화합니다. |
| [setRange(String formula)](#setRange-java.lang.String-) | 차트 데이터 범위를 설정합니다. |
| [getRange()](#getRange--) | 차트 데이터 범위를 가져옵니다. |
| [getDataSourceType()](#getDataSourceType--) | 차트의 데이터 원본을 나타냅니다 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 데이터 원본이 외부인 경우 외부 워크북 경로를 나타내며, 그렇지 않으면 null입니다. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 내장 워크북의 유형을 가져옵니다. |
| [switchRowColumn()](#switchRowColumn--) | 축을 따라 데이터를 교환합니다. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 외부 워크북을 차트의 데이터 원본으로 설정합니다. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 외부 워크북을 차트의 데이터 원본으로 설정합니다. |
| [refreshData()](#refreshData--) | 소스 워크북에서 다시 로드하여 차트 데이터를 새로 고칩니다. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

차트 시리즈 또는 범주에 사용되는 셀을 생성하는 셀 팩토리를 가져옵니다. 읽기 전용 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**반환:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

시리즈를 가져옵니다. 읽기 전용 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**반환:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

시리즈 그룹을 가져옵니다. 읽기 전용 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) 각 시리즈 그룹은 결합 가능한 유형의 시리즈를 포함합니다. 결합 가능한 시리즈 유형은 CombinableSeriesTypesGroup 열거형으로 정의 및 설명됩니다. 또한 각 시리즈 그룹은 기본 축이나 보조 축에 플롯되는 시리즈를 포함하지만 하나의 그룹에 두 축이 동시에 포함되지는 않습니다. 따라서 시리즈 그룹화 원칙은 앞서 언급한 유형 그룹과 기본/보조 플롯 유형에 따라 그룹화됩니다. 2) 시리즈 그룹은 그룹 내 모든 시리즈에 공통인 일부 시리즈 속성을 포함합니다("시리즈 그룹 속성"). ChartSeriesGroup 클래스의 "시리즈 그룹 속성"은 읽기/쓰기 가능합니다. 각 "시리즈 그룹 속성"은 ChartSeries 클래스에서 읽기 전용 투영을 가질 수 있습니다.

**반환:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

기본 범주를 가져옵니다 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 속성이 false인 경우 기본 및 보조 범주를 모두 가져옵니다. 읽기 전용 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 관련 범주는 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 관련 범주는 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

false이면 (\#getSecondaryCategories.getSecondaryCategories) 속성이 null을 반환하고 이 (\#getCategories.getCategories) 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true이면 (\#getSecondaryCategories.getSecondaryCategories) 속성의 데이터가 보조 시리즈에, 이 (\#getCategories.getCategories) 속성의 데이터가 기본 시리즈에 사용됩니다.

**반환:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

false이면 (\#getSecondaryCategories.getSecondaryCategories) 속성이 null을 반환하고 (\#getCategories.getCategories) 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true이면 (\#getSecondaryCategories.getSecondaryCategories) 속성의 데이터가 보조 시리즈에, (\#getCategories.getCategories) 속성의 데이터가 기본 시리즈에 사용됩니다. 읽기/쓰기 부울.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 관련 범주는 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 관련 범주는 series.getChart().getChartData().getCategories()
>  }
> ```

**반환:**  
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

false이면 (\#getSecondaryCategories.getSecondaryCategories) 속성이 null을 반환하고 (\#getCategories.getCategories) 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true이면 (\#getSecondaryCategories.getSecondaryCategories) 속성의 데이터가 보조 시리즈에, (\#getCategories.getCategories) 속성의 데이터가 기본 시리즈에 사용됩니다. 읽기/쓰기 부울.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 관련 범주는 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 관련 범주는 series.getChart().getChartData().getCategories()
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

보조 범주를 가져옵니다 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 속성이 true인 경우. 읽기 전용 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 관련 범주는 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 관련 범주는 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

false이면 이 (\#getSecondaryCategories.getSecondaryCategories) 속성이 null을 반환하고 (\#getCategories.getCategories) 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true이면 이 (\#getSecondaryCategories.getSecondaryCategories) 속성의 데이터가 보조 시리즈에, (\#getCategories.getCategories) 속성의 데이터가 기본 시리즈에 사용됩니다.

**반환:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

내부에 포함된 Excel 워크북을 메모리 스트림에 씁니다.

**반환:**  
byte[] - 내부에 포함된 Excel 워크북의 복사본을 포함하는 바이트 배열을 반환합니다.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

내부에 포함된 Excel 워크북을 사용자가 지정한 값으로 초기화합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ms | byte[] | 전체 Excel 워크북을 포함하는 사용자 제공 스트림입니다. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

차트 데이터 범위를 설정합니다. 새 데이터 범위에 따라 시리즈와 범주가 업데이트됩니다. 데이터 범위의 시리즈 수가 차트 데이터의 시리즈 수보다 많으면 현재 컬렉션의 마지막 시리즈와 동일한 유형의 추가 시리즈가 컬렉션 끝에 추가됩니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formula | java.lang.String | 셀 데이터 범위 수식입니다. 예: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

차트 데이터 범위를 가져옵니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**반환:**  
java.lang.String - 셀 데이터 범위 수식입니다. 예: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

차트의 데이터 원본을 나타냅니다

**반환:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

데이터 원본이 외부인 경우 외부 워크북 경로를 나타내며, 그렇지 않으면 null입니다

**반환:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

내장 워크북의 유형을 가져옵니다. DataSourceType (\#getDataSourceType.getDataSourceType) 가 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)인 경우 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)을 반환합니다. 읽기 전용 [WorkbookType](../../com.aspose.slides/workbooktype).

**반환:**  
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

축을 따라 데이터를 교환합니다. X 축에 차트된 데이터가 Y 축으로 이동하고 그 반대도 마찬가지입니다.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

외부 워크북을 차트의 데이터 원본으로 설정합니다. 차트 데이터가 대상 워크북에서 업데이트됩니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| workbookPath | java.lang.String | 대상 워크북의 경로 |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

외부 워크북을 차트의 데이터 원본으로 설정합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| workbookPath | java.lang.String | 대상 워크북의 경로 |
| updateChartData | boolean | 값이 false이면 워크북 경로만 업데이트됩니다. 차트 데이터는 로드되거나 대상 워크북에서 업데이트되지 않습니다. 대상 워크북이 존재하지 않거나 사용할 수 없을 때 사용할 수 있습니다. 값이 true이면 차트 데이터가 대상 워크북에서 업데이트됩니다. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

소스 워크북에서 다시 로드하여 차트 데이터를 새로 고칩니다.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```