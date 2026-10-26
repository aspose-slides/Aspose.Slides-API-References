---
title: ChartDataPointCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/chartdatapointcollection/
---
## ChartDataPointCollection 类

 表示系列数据点的集合。

### addDataPointForAreaSeries {#addDataPointForAreaSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForAreaSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Area 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeArea(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForAreaSeries {#addDataPointForAreaSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForAreaSeries (double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Area 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeArea(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBarSeries {#addDataPointForBarSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBarSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Column 或 Bar 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeColumn(int) 和 ChartTypeCharacterizer#isChartTypeBar(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBarSeries {#addDataPointForBarSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBarSeries (double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Column 或 Bar 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeColumn(int) 和 ChartTypeCharacterizer#isChartTypeBar(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBoxAndWhiskerSeries {#addDataPointForBoxAndWhiskerSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBoxAndWhiskerSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于图表类型为 BoxAndWhisker 的系列。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries ([ChartDataCell](../chartdatacell), [ChartDataCell](../chartdatacell), [ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [ChartDataCell](../chartdatacell) | 数据点 XValue |
| yValue | [ChartDataCell](../chartdatacell) | 数据点 YValue |
| bubbleSize | [ChartDataCell](../chartdatacell) | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries (double, [ChartDataCell](../chartdatacell), [ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | [ChartDataCell](../chartdatacell) | 数据点 YValue |
| bubbleSize | [ChartDataCell](../chartdatacell) | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries (String, [ChartDataCell](../chartdatacell), [ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | String | 数据点 XValue |
| yValue | [ChartDataCell](../chartdatacell) | 数据点 YValue |
| bubbleSize | [ChartDataCell](../chartdatacell) | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries ([ChartDataCell](../chartdatacell), double, [ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [ChartDataCell](../chartdatacell) | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | [ChartDataCell](../chartdatacell) | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries (double, double, [ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | [ChartDataCell](../chartdatacell) | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries (String, double, [ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | String | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | [ChartDataCell](../chartdatacell) | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries ([ChartDataCell](../chartdatacell), [ChartDataCell](../chartdatacell), double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [ChartDataCell](../chartdatacell) | 数据点 XValue |
| yValue | [ChartDataCell](../chartdatacell) | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries (double, [ChartDataCell](../chartdatacell), double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | [ChartDataCell](../chartdatacell) | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries (String, [ChartDataCell](../chartdatacell), double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | String | 数据点 XValue |
| yValue | [ChartDataCell](../chartdatacell) | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries ([ChartDataCell](../chartdatacell), double, double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [ChartDataCell](../chartdatacell) | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries (double, double, double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForBubbleSeries {#addDataPointForBubbleSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForBubbleSeries (String, double, double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeBubble(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | String | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForDoughnutSeries {#addDataPointForDoughnutSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForDoughnutSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeDoughnut(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForDoughnutSeries {#addDataPointForDoughnutSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForDoughnutSeries (double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeDoughnut(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForFunnelSeries {#addDataPointForFunnelSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForFunnelSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于图表类型为 Funnel 的系列。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForHistogramSeries {#addDataPointForHistogramSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForHistogramSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于图表类型为 Histogram 的系列。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForLineSeries {#addDataPointForLineSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForLineSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Line 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeLine(int) 方法）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值。 |

**返回值:**
[ChartDataPoint](../chartdatapoint)

---
| addDataPointForLineSeries (double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Line 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeLine(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值。 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForMapSeries {#addDataPointForMapSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForMapSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chart type 为 Map 的系列。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点 ColorValue |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForPieSeries {#addDataPointForPieSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForPieSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Pie 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypePie(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForPieSeries {#addDataPointForPieSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForPieSeries (double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Pie 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypePie(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForRadarSeries {#addDataPointForRadarSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForRadarSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeRadar(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForRadarSeries {#addDataPointForRadarSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForRadarSeries (double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeRadar(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForScatterSeries {#addDataPointForScatterSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForScatterSeries ([ChartDataCell](../chartdatacell), [ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeScatter(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [ChartDataCell](../chartdatacell) | 数据点 XValue |
| yValue | [ChartDataCell](../chartdatacell) | 数据点 YValue |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForScatterSeries {#addDataPointForScatterSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForScatterSeries (double, [ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeScatter(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | [ChartDataCell](../chartdatacell) | 数据点 YValue |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForScatterSeries {#addDataPointForScatterSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForScatterSeries (String, [ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeScatter(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | String | 数据点 XValue |
| yValue | [ChartDataCell](../chartdatacell) | 数据点 YValue |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForScatterSeries {#addDataPointForScatterSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForScatterSeries ([ChartDataCell](../chartdatacell), double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeScatter(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [ChartDataCell](../chartdatacell) | 数据点 XValue |
| yValue | double | 数据点 YValue |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForScatterSeries {#addDataPointForScatterSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForScatterSeries (double, double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeScatter(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | double | 数据点 YValue |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForScatterSeries {#addDataPointForScatterSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForScatterSeries (String, double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeScatter(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xValue | String | 数据点 XValue |
| yValue | double | 数据点 YValue |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForStockSeries {#addDataPointForStockSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForStockSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Stock 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeStock(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值。 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForStockSeries {#addDataPointForStockSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForStockSeries (double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Stock 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeStock(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值。 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForSunburstSeries {#addDataPointForSunburstSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForSunburstSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chart type 为 Sunburst 的系列。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sizeValue | [ChartDataCell](../chartdatacell) | 数据点 SizeValue |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForSurfaceSeries {#addDataPointForSurfaceSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForSurfaceSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Surface 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeSurface(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForSurfaceSeries {#addDataPointForSurfaceSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForSurfaceSeries (double) | 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Surface 子类型之一的系列（另请参阅 ChartTypeCharacterizer#isChartTypeSurface(int) 方法）。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForTreemapSeries {#addDataPointForTreemapSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForTreemapSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chart type 为 Treemap 的系列。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sizeValue | [ChartDataCell](../chartdatacell) | 数据点 SizeValue |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### addDataPointForWaterfallSeries {#addDataPointForWaterfallSeries}

| 名称 | 描述 |
| --- | --- |
| addDataPointForWaterfallSeries ([ChartDataCell](../chartdatacell)) | 创建新的数据点并将其添加到集合的末尾。适用于 chart type 为 Waterfall 的系列。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataCell](../chartdatacell) | 数据点值 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有元素。 |

**Returns:**
void

---

### getDataSourceTypeForBubbleSizes {#getDataSourceTypeForBubbleSizes}

| 名称 | 描述 |
| --- | --- |
| getDataSourceTypeForBubbleSizes () | 指定在数据点的 BubbleSize 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.BubbleSize.Data 属性的值类型。可读写 DataSourceType。 |

**Returns:**
int

---

### getDataSourceTypeForErrorBarsCustomValues {#getDataSourceTypeForErrorBarsCustomValues}

| 名称 | 描述 |
| --- | --- |
| getDataSourceTypeForErrorBarsCustomValues () | 指定 ChartDataPoint.ErrorBarsCustomValues 属性列表中值的类型。只读 IDataSourceTypeForErrorBarsCustomValues。 |

**Returns:**
[DataSourceTypeForErrorBarsCustomValues](../datasourcetypeforerrorbarscustomvalues)

---

### getDataSourceTypeForValues {#getDataSourceTypeForValues}

| 名称 | 描述 |
| --- | --- |
| getDataSourceTypeForValues () | 指定在数据点的 Value 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.Value.Data 属性的值类型。可读写 DataSourceType。 |

**Returns:**
int

---

### getDataSourceTypeForXValues {#getDataSourceTypeForXValues}

| 名称 | 描述 |
| --- | --- |
| getDataSourceTypeForXValues () | 指定在数据点的 XValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.XValue.Data 属性的值类型。可读写 DataSourceType。 |

**Returns:**
int

---

### getDataSourceTypeForYValues {#getDataSourceTypeForYValues}

| 名称 | 描述 |
| --- | --- |
| getDataSourceTypeForYValues () | 指定在数据点的 YValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.YValue.Data 属性的值类型。可读写 DataSourceType。 |

**Returns:**
int

---

### getOrCreateDataPointByIdx {#getOrCreateDataPointByIdx}

| 名称 | 描述 |
| --- | --- |
| getOrCreateDataPointByIdx (long) | 如果集合已经包含索引为 index 的数据点，则返回该数据点。如果集合不包含索引为 index==N 的数据点（当此集合中的数据点数量小于或等于 N 时），则添加缺失的数据点并返回最后一个（即请求的索引）。例如，集合索引为 {0, 1, 2}，请求的索引为 5。则方法添加缺失的数据点：{0, 1, 2, 3, 4, 5}。并返回索引为 5 的数据点。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | long | 索引。 |

**Returns:**
[ChartDataPoint](../chartdatapoint)

---

### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回一个同步根。只读 Object。 |

**返回:**
Object


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 返回按索引（此集合中的序列号）获取的系列数据点。 |

**返回:**
[ChartDataPoint](../chartdatapoint)


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item ([ChartDataPoint](../chartdatapoint)) | 返回此集合中数据点的索引（序列号）。 |

**返回:**
int


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个指示集合访问是否同步（线程安全）的值。只读 boolean。 |

**返回:**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个遍历集合的枚举器。 |

**返回:**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回:**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([ChartDataPoint](../chartdatapoint)) | 移除指定的值。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartDataPoint](../chartdatapoint) | 该值。 |

**返回:**
void


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 移除给定索引处的元素。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的数据点的索引。 |

**返回:**
void


---


### setDataSourceTypeForBubbleSizes {#setDataSourceTypeForBubbleSizes}

| 名称 | 描述 |
| --- | --- |
| setDataSourceTypeForBubbleSizes (int) | 指定在数据点 BubbleSize 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.BubbleSize.Data 属性值的类型。读/写 DataSourceType。 |

**返回:**
void


---


### setDataSourceTypeForValues {#setDataSourceTypeForValues}

| 名称 | 描述 |
| --- | --- |
| setDataSourceTypeForValues (int) | 指定在数据点 Value 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.Value.Data 属性值的类型。读/写 DataSourceType。 |

**返回:**
void


---


### setDataSourceTypeForXValues {#setDataSourceTypeForXValues}

| 名称 | 描述 |
| --- | --- |
| setDataSourceTypeForXValues (int) | 指定在数据点 XValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.XValue.Data 属性值的类型。读/写 DataSourceType。 |

**返回:**
void


---


### setDataSourceTypeForYValues {#setDataSourceTypeForYValues}

| 名称 | 描述 |
| --- | --- |
| setDataSourceTypeForYValues (int) | 指定在数据点 YValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.YValue.Data 属性值的类型。读/写 DataSourceType。 |

**返回:**
void


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 获取集合中实际包含的元素数量。只读 int。 |

**返回:**
int


---