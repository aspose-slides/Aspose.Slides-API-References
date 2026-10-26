---
title: StringChartValue
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/stringchartvalue/
---
## StringChartValue 类

表示可以在 pptx 演示文稿中以两种方式存储的字符串值：
1) 在与图表关联的工作簿的单元格中；
2) 作为文字值。

### getAsCells {#getAsCells}

| Name | Description |
| --- | --- |
| getAsCells () | 不允许分配空值。返回值始终不为 null。读/写 IChartCellCollection. |

**返回值:**
[ChartCellCollection](../chartcellcollection)

---

### getAsLiteralString {#getAsLiteralString}

| Name | Description |
| --- | --- |
| getAsLiteralString () | 返回或设置为文字字符串。读/写 String. |

**返回值:**
String

---

### getCellsAddressInWorkbook {#getCellsAddressInWorkbook}

| Name | Description |
| --- | --- |
| getCellsAddressInWorkbook () | 如果 DataSourceType 属性为 DataSourceType.Worksheet，则此方法返回工作簿中对应字符串数据的单元格地址。否则返回空字符串。 |

**返回值:**
String

---

### getData {#getData}

| Name | Description |
| --- | --- |
| getData () | 返回或设置 Data 对象。读/写 Object. |

**返回值:**
Object

---

### setAsCells {#setAsCells}

| Name | Description |
| --- | --- |
| setAsCells ([ChartCellCollection](../chartcellcollection)) | 不允许分配空值。返回值始终不为 null。读/写 IChartCellCollection. |

**返回值:**
void

---

### setAsLiteralString {#setAsLiteralString}

| Name | Description |
| --- | --- |
| setAsLiteralString (String) | 返回或设置为文字字符串。读/写 String. |

**返回值:**
void

---

### setData {#setData}

| Name | Description |
| --- | --- |
| setData (Object) | 返回或设置 Data 对象。读/写 Object. |

**返回值:**
void

---

### setFromOneCell {#setFromOneCell}

| Name | Description |
| --- | --- |
| setFromOneCell ([ChartDataCell](../chartdatacell)) | 从指定单元格设置值。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| cell | [ChartDataCell](../chartdatacell) | Cell. |

**返回值:**
void

---

### toString {#toString}

| Name | Description |
| --- | --- |
| toString () | 返回字符串值数据。如果 DataSourceType 为 false 且未分配字符串值，则返回 null。 |

**返回值:**
String

---