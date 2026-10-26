---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Java API Reference
description: Specifies the errors bar values.
type: docs
url: /th/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

ระบุค่าบาร์ความผิดพลาด จะต้องใช้เฉพาะเมื่อประเภทค่าบาร์ความผิดพลาดเป็น Custom.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXMinus()](#getXMinus--) | ระบุค่าบาร์ความผิดพลาดในทิศทางลบ. |
| [getYMinus()](#getYMinus--) | ระบุค่าบาร์ความผิดพลาดในทิศทางลบ. |
| [getXPlus()](#getXPlus--) | ระบุค่าบาร์ความผิดพลาดในทิศทางบวก. |
| [getYPlus()](#getYPlus--) | ระบุค่าบาร์ความผิดพลาดในทิศทางบวก. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

ระบุค่าบาร์ความผิดพลาดในทิศทางลบ. พร้อมใช้งานหากประเภทค่าบาร์ความผิดพลาดคือ Custom และ ErrorBarsXFormat ได้รับอนุญาต. ในกรณีอื่น ๆ คุณสมบัตินี้จะคืนค่า null. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

ระบุค่าบาร์ความผิดพลาดในทิศทางลบ. พร้อมใช้งานหากประเภทค่าบาร์ความผิดพลาดคือ Custom และ ErrorBarsYFormat ได้รับอนุญาต. ในกรณีอื่น ๆ คุณสมบัตินี้จะคืนค่า null. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

ระบุค่าบาร์ความผิดพลาดในทิศทางบวก. พร้อมใช้งานหากประเภทค่าบาร์ความผิดพลาดคือ Custom และ ErrorBarsXFormat ได้รับอนุญาต. ในกรณีอื่น ๆ คุณสมบัตินี้จะคืนค่า null. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

ระบุค่าบาร์ความผิดพลาดในทิศทางบวก. พร้อมใช้งานหากประเภทค่าบาร์ความผิดพลาดคือ Custom และ ErrorBarsYFormat ได้รับอนุญาต. ในกรณีอื่น ๆ คุณสมบัตินี้จะคืนค่า null. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)