---
title: IErrorBarsCustomValues
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định các giá trị của thanh lỗi.
type: docs
url: /vi/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Xác định các giá trị của thanh lỗi. Nó chỉ được sử dụng khi kiểu giá trị thanh lỗi là Custom.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getXMinus()](#getXMinus--) | Xác định giá trị thanh lỗi theo hướng âm. |
| [getYMinus()](#getYMinus--) | Xác định giá trị thanh lỗi theo hướng âm. |
| [getXPlus()](#getXPlus--) | Xác định giá trị thanh lỗi theo hướng dương. |
| [getYPlus()](#getYPlus--) | Xác định giá trị thanh lỗi theo hướng dương. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Xác định giá trị thanh lỗi theo hướng âm. Có sẵn nếu kiểu giá trị thanh lỗi là Custom và ErrorBarsXFormat được cho phép. Trong mọi trường hợp khác thuộc tính này sẽ trả về null. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Xác định giá trị thanh lỗi theo hướng âm. Có sẵn nếu kiểu giá trị thanh lỗi là Custom và ErrorBarsYFormat được cho phép. Trong mọi trường hợp khác thuộc tính này sẽ trả về null. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Xác định giá trị thanh lỗi theo hướng dương. Có sẵn nếu kiểu giá trị thanh lỗi là Custom và ErrorBarsXFormat được cho phép. Trong mọi trường hợp khác thuộc tính này sẽ trả về null. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Xác định giá trị thanh lỗi theo hướng dương. Có sẵn nếu kiểu giá trị thanh lỗi là Custom và ErrorBarsYFormat được cho phép. Trong mọi trường hợp khác thuộc tính này sẽ trả về null. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)