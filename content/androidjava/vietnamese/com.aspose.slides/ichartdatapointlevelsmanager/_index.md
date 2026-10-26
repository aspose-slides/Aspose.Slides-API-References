---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Bộ chứa các cấp độ điểm dữ liệu.
type: docs
url: /vi/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Bộ chứa các cấp độ điểm dữ liệu. Áp dụng cho các series Treeamp và Sunburst. Chỉ mục các cấp độ điểm dữ liệu bắt đầu từ 0.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Trả về đối tượng IChartDataPointLevel cho cấp độ đã xác định. |
| [getCount()](#getCount--) | Trả về số lượng cấp độ điểm dữ liệu. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


Trả về đối tượng IChartDataPointLevel cho cấp độ đã xác định.

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


Trả về số lượng cấp độ điểm dữ liệu.

**Trả về:**
int