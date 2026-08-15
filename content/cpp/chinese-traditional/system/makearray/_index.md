---
title: MakeArray()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新 Array 物件的工廠函式，將指定初始化清單中的元素填入該物件，並返回指向該 Array 物件的智慧指標。
type: docs
weight: 2029
url: /zh-hant/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) 函式


此工廠函式會建立一個新的 [Array](../array/) 物件，將指定的初始化列表中的元素填入該物件，並返回指向 [Array](../array/) 物件的智慧指標。

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Array](../array/) 物件所建構之元素的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| init | std::initializer_list\<T\> | 包含用於填充陣列之元素的初始化清單 |

### 返回值

指向已建構 [Array](../array/) 物件的智慧指標

## System::MakeArray(Args\&&...) 函式


此工廠函式會建立一個新的 [Array](../array/) 物件，將指定的參數傳遞給其建構函式。

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Array](../array/) 物件所建構之元素的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| args | Args\&&... | 傳遞給正被建構的 [Array](../array/) 物件之建構函式的參數 |

### 返回值

指向已建構 [Array](../array/) 物件的智慧指標

## System::MakeArray(Integral, Args\&&...) 函式


此工廠函式會建立一個新的 [Array](../array/) 物件，將指定的參數傳遞給其建構函式。

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Array](../array/) 物件所建構之元素的型別 |
| Integral | 陣列大小的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| size | Integral | 正在建立之陣列的大小 |
| args | Args\&&... | 傳遞給正被建構的 [Array](../array/) 物件之建構函式的參數 |

### 返回值

指向已建構 [Array](../array/) 物件的智慧指標

## 另請參閱

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)