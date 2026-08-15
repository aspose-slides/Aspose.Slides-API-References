---
title: Decimal()
second_title: Aspose.Slides for C++ API 參考
description: 建立代表 0 的實例。
type: docs
weight: 1
url: /zh-hant/system/decimal/decimal/
---
## Decimal::Decimal() 建構函式

建立一個代表 0 的實例。

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | std::int8_t | 由即將建構的 [Decimal](../) 物件所表示的 8 位元整數值 |

## Decimal::Decimal(std::int16_t) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | std::int16_t | 由即將建構的 [Decimal](../) 物件所表示的 16 位元整數值 |

## Decimal::Decimal(std::int32_t) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | std::int32_t | 由即將建構的 [Decimal](../) 物件所表示的 32 位元整數值 |

## Decimal::Decimal(std::int64_t) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | std::int64_t | 由即將建構的 [Decimal](../) 物件所表示的 64 位元整數值 |

## Decimal::Decimal(std::uint8_t) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | std::uint8_t | 由即將建構的 [Decimal](../) 物件所表示的無號 8 位元整數值 |

## Decimal::Decimal(std::uint16_t) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | std::uint16_t | 由即將建構的 [Decimal](../) 物件所表示的無號 16 位元整數值 |

## Decimal::Decimal(std::uint32_t) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | std::uint32_t | 由即將建構的 [Decimal](../) 物件所表示的無號 32 位元整數值 |

## Decimal::Decimal(std::uint64_t) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | std::uint64_t | 由即將建構的 [Decimal](../) 物件所表示的無號 64 位元整數值 |

## Decimal::Decimal(float) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(float f)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| f | **float** | 由即將建構的 [Decimal](../) 物件所表示的單精度浮點值 |

## Decimal::Decimal(double) 建構函式

建立一個代表指定值的實例。

```cpp
System::Decimal::Decimal(double d)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| d | **double** | 由即將建構的 [Decimal](../) 物件所表示的雙精度浮點值 |

## Decimal::Decimal(const std::string\&) 建構函式

建立一個以 std::string 類別實例所指定的字串表示形式為值的實例。

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) 建構函式

從指定的組件建構一個 [Decimal](../) 物件。

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lo | **int32_t** | 值的低 32 位元 |
| mid | **int32_t** | 值的中間 32 位元 |
| hi | **int32_t** | 值的高 32 位元 |
| isNegative | **bool** | 指定值是否為負數 |
| scale | **uint8_t** | 介於 0 到 28 之間的 10 的次方 |

## Decimal::Decimal(const Decimal\&) 建構函式

建立一個與指定 [Decimal](../) 物件代表相同數值的 [Decimal](../) 類別實例。

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| d | const [Decimal](../)\& | 用於複製數值的 [Decimal](../) 物件 |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) 建構函式

從包含二進位表示的整數陣列建構 [Decimal](../) 類別的實例。

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | 包含二進位表示的整數陣列。 |

## Decimal::Decimal(std::nullptr_t) 建構函式

永遠拋出 ArgumentNullException。

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) 建構函式

建立一個代表指定值的 [Decimal](../) 類別實例。

```cpp
System::Decimal::Decimal(const number_type &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | 要由即將建構的物件表示的常量參考值 |

## 相關參考

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)