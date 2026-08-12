---
title: Round()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด.
type: docs
weight: 157
url: /th/system/math/round/
---
## Math::Round(double) เมธอด

ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด.

```cpp
static double System::Math::Round(double a)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | **double** | The value to round |

### Return Value

**a** ปัดเป็นค่าจำนวนเต็มที่ใกล้ที่สุด

## Math::Round(double, int) เมธอด

ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ

```cpp
static double System::Math::Round(double value, int digits)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | The value to round |
| digits | int | The number of fractional digits in the rounded value |

### Return Value

ตัวเลขที่มีจำนวนตำแหน่งทศนิยมตามที่ระบุและใกล้ที่สุดกับ **value**

## Math::Round(double, MidpointRounding) เมธอด

ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด พารามิเตอร์กำหนดพฤติกรรมของฟังก์ชันเมื่อค่าที่ระบุอยู่ห่างเท่ากันจากตัวเลขสองค่าที่ใกล้ที่สุด

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | The value to round |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

**value** ปัดเป็นค่าจำนวนเต็มที่ใกล้ที่สุด

## Math::Round(double, int, MidpointRounding) เมธอด

ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ พารามิเตอร์กำหนดพฤติกรรมของฟังก์ชันเมื่อค่าที่ระบุอยู่ห่างเท่ากันจากตัวเลขสองค่าที่ใกล้ที่สุด

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | The value to round |
| digits | int | The number of fractional digits in the rounded value |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

ตัวเลขที่มีจำนวนตำแหน่งทศนิยมตามที่ระบุและใกล้ที่สุดกับ **value**

## Math::Round(const Decimal\&) เมธอด

ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | The value to round |

### Return Value

**d** ปัดเป็นค่าจำนวนเต็มที่ใกล้ที่สุด

## Math::Round(const Decimal\&, int) เมธอด

ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | The value to round |
| digits | int | The number of fractional digits in the rounded value |

### Return Value

ตัวเลขที่มีจำนวนตำแหน่งทศนิยมตามที่ระบุและใกล้ที่สุดกับ **value**

## Math::Round(const Decimal\&, MidpointRounding) เมธอด

ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด พารามิเตอร์กำหนดพฤติกรรมของฟังก์ชันเมื่อค่าที่ระบุอยู่ห่างเท่ากันจากตัวเลขสองค่าที่ใกล้ที่สุด.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | The value to round |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

**d** ปัดเป็นค่าจำนวนเต็มที่ใกล้ที่สุด

## Math::Round(const Decimal\&, int, MidpointRounding) เมธอด

ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ พารามิเตอร์กำหนดพฤติกรรมของฟังก์ชันเมื่อค่าที่ระบุอยู่ห่างเท่ากันจากตัวเลขสองค่าที่ใกล้ที่สุด.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | The value to round |
| digits | int | The number of fractional digits in the rounded value |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

ตัวเลขที่มีจำนวนตำแหน่งทศนิยมตามที่ระบุและใกล้ที่สุดกับ **value**

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* คลาส [Decimal](../../decimal/)
* โครงสร้าง [Math](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)