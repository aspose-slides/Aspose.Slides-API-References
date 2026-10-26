---
title: Sign()
second_title: Aspose.Slides for C++ API 參考文件
description: 判定指定有號整數值的符號。
type: docs
weight: 274
url: /zh-hant/system/math/sign/
---
## Math::Sign(T) 方法

判定指定有號整數值的符號。

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | The integral signed type |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The value to determine the sign of |

### 回傳值

- 1 if **value** is less than 0; 0 if **value** is equal to 0; 1 if **value** is greater than 0

## Math::Sign(T) 方法

判定指定浮點數值的符號。

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | The floating point type of the argument |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The value to determine the sign of |

### 回傳值

- 1 if **value** is less than 0; 0 if **value** is equal to 0; 1 if **value** is greater than 0

## Math::Sign(const Decimal\&) 方法

判定指定十進位值的符號。

```cpp
static int System::Math::Sign(const Decimal &value)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | The value to determine the sign of |

### 回傳值

- 1 if **value** is less than 0; 0 if **value** is equal to 0; 1 if **value** is greater than 0

## 另見

* 類別 [Decimal](../../decimal/)
* 結構 [Math](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)