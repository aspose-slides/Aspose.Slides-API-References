---
title: Exchange()
second_title: Aspose.Slides for C++ API 參考
description: "交換變數的值：儲存新值，並回傳變數在儲存前的原始值。"
type: docs
weight: 66
url: /zh-hant/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) 方法

在變數上交換值：儲存新值，並回傳變數在儲存前的先前值。

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 變數類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| location1 | T\& | 要變更的變數參考。 |
| value | T | 要儲存的值。 |

### 返回值

變數在變更前的值。

## Interlocked::Exchange(T\&, T) 方法

在變數上交換值：儲存新值，並回傳變數在儲存前的先前值。未實作。

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 變數類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| location1 | T\& | 要變更的變數參考。 |
| value | T | 要儲存的值。 |

### 返回值

變數在變更前的值。

## 參見

* 類別 [Interlocked](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)