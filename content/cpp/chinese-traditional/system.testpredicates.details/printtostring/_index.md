---
title: PrintToString()
second_title: Aspose.Slides for C++ API 參考文件
description: 透過選擇適當的序列化函式，將物件列印為字串。
type: docs
weight: 1
url: /zh-hant/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) function


透過選擇適當的序列化函式，將物件列印為字串。

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 引數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 以列印。 |

### 傳回值

[String](../../system/string/) 物件的表示形式。

## System::TestPredicates::Details::PrintToString(const T\&) function


將 ICollection 風格的容器列印為字串，列印其元素（最多 32 個）。

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 引數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 以列印。 |

### 傳回值

將包含的元素合併為字串表示。

## System::TestPredicates::Details::PrintToString(std::nullptr_t) function


將 nullptr 列印為字串。

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```


### 傳回值

\"nullptr\" 字串。

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) function


將 [IEnumerable<bool>](../../system.collections.generic/ienumerable/) 集合列印為字串，列印其元素（最多 32 個）。

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 引數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) 以列印。 |

### 傳回值

將包含的元素合併為字串表示。

## 參見

* 類別 [IEnumerable](../../system.collections.generic/ienumerable/)
* 結構體 [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* 命名空間 [System::TestPredicates::Details](../)
* 函式庫 [Aspose.Slides](../../)