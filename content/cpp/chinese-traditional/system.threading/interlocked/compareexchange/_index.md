---
title: CompareExchange()
second_title: Aspose.Slides for C++ API 參考文件
description: "比較並交換變數的值：檢查變數是否等於特定值，僅在已儲存的值與預期值相符時才儲存新值。"
type: docs
weight: 79
url: /zh-hant/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) 方法


比較並交換變數的值：檢查變數是否等於特定值，僅在已儲存的值與期望值相符時才儲存新值。

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 變數類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| location1 | T\& | 要變更的變數參考。 |
| value | T | 要儲存的值。 |
| comparand | T | 交換前用於比較變數值的值。 |

### 返回值

操作開始時變數的值，無論是否已更改。

## Interlocked::CompareExchange(T\&, T, T) 方法


比較並交換變數的值：檢查變數是否等於特定值，僅在已儲存的值與期望值相符時才儲存新值。未實作。

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 變數類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| location1 | T\& | 要變更的變數參考。 |
| value | T | 要儲存的值。 |
| comparand | T | 交換前用於比較變數值的值。 |

### 返回值

操作開始時變數的值，無論是否已更改。

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) 方法


比較並交換變數的值：檢查變數是否等於特定值，僅在已儲存的值與期望值相符時才儲存新值。

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| location1 | **int32_t**\& | 要變更的變數參考。 |
| value | **int32_t** | 要儲存的值。 |
| comparand | **int32_t** | 交換前用於比較變數值的值。 |
| succeeded | **bool**\& | 參考變數；若交換發生則設為 true，否則設為 false。 |

### 返回值

操作開始時變數的值，無論是否已更改。

## 另請參閱

* 類別 [Interlocked](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)