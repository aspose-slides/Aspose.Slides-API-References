---
title: Next()
second_title: Aspose.Slides for C++ API 參考手冊
description: 傳回小於 int32 最大值的非負隨機數。
type: docs
weight: 27
url: /zh-hant/system/random/next/
---
## Random::Next() 方法

傳回小於 int32 最大值的非負隨機數。

```cpp
virtual int32_t System::Random::Next()
```

## Random::Next(int32_t) 方法

傳回小於指定最大值的非負隨機數。

```cpp
virtual int32_t System::Random::Next(int32_t maxValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| maxValue | **int32_t** | 此方法產生的值將小於此值 |

## Random::Next(int32_t, int32_t) 方法

傳回位於指定範圍內的隨機數。

```cpp
virtual int32_t System::Random::Next(int32_t minValue, int32_t maxValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| minValue | **int32_t** | 此方法產生的值將大於此值 |
| maxValue | **int32_t** | 此方法產生的值將小於此值 |

## 另請參閱

* 類別 [Random](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)