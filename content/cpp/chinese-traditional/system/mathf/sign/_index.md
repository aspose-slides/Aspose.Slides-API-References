---
title: Sign()
second_title: Aspose.Slides for C++ API 參考
description: 確定指定的有號整數值的符號。
type: docs
weight: 274
url: /zh-hant/system/mathf/sign/
---
## MathF::Sign(T) 方法

確定指定的有號整數值的符號。

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | The integral signed type |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | T | The value to determine the sign of |

### 返回值

- 1 if **value** is less than 0; 0 if **value** is equal to 0; 1 if **value** is greater than 0

## MathF::Sign(T) 方法

確定指定的浮點值的符號。

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | The floating point type of the argument |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | T | The value to determine the sign of |

### 返回值

- 1 if **value** is less than 0; 0 if **value** is equal to 0; 1 if **value** is greater than 0

## 另請參閱

* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)