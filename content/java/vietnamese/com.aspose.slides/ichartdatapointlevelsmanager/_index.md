---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Bộ chứa các mức dữ liệu điểm.
type: docs
url: /vi/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Bộ chứa các mức dữ liệu điểm. Áp dụng cho các chuỗi Treeamp và Sunburst. Chỉ mục các mức dữ liệu điểm bắt đầu từ số 0.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Trả về đối tượng IChartDataPointLevel cho mức đã xác định. |
| [getCount()](#getCount--) | Trả về số lượng mức dữ liệu điểm. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

Trả về đối tượng IChartDataPointLevel cho mức đã xác định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| level | int |  |

**Trả về:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Trả về số lượng mức dữ liệu điểm.

**Trả về:**
int