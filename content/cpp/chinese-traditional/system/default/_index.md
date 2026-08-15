---
title: Default()
second_title: Aspose.Slides for C++ API 參考
description: 返回例外類型的單一預設建構實例的參考。
type: docs
weight: 2224
url: /zh-hant/system/default/
---
## System::Default() 函式

返回對例外類型的單一預設建構實例的參考。

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 返回其實例的類型 |

## System::Default() 函式

返回對非例外類型的單一預設建構實例的參考。

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 返回其實例的類型 |

## 另見

* 結構 [IsExceptionWrapper](../isexceptionwrapper/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)