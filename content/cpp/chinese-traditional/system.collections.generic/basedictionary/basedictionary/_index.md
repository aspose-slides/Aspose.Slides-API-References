---
title: BaseDictionary()
second_title: Aspose.Slides for C++ API 參考
description: 建立空的資料結構。
type: docs
weight: 14
url: /zh-hant/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() 建構函式


建立空的資料結構。

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) 建構函式


轉發建構式，用於將參數推送至底層 map 建構式。

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| Args | 要轉發至 map 的參數類型。 |

### 引數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| args | int | 要轉發至底層 map 的參數。 |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) 建構函式


複製建構式。

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| Args | map 建構式參數的類型。 |

### 引數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) 以從中複製資料。 |
| args | const Args\&... | 要轉發至底層 map 建構式的參數。 |

## BaseDictionary::BaseDictionary(BaseType *) 建構函式


複製建構式。

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```


### 引數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) 以從中複製資料。 |

## 另請參閱

* 型別別名 [BaseType](../basetype/)
* 類別 [BaseDictionary](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)