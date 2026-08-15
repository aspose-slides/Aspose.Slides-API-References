---
title: CastEnumerableTo()
second_title: Aspose.Slides for C++ API 參考
description: 對指定的可列舉物件的元素執行顯式型別轉換為不同的類型。
type: docs
weight: 2965
url: /zh-hant/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) function

對指定的可列舉物件的元素執行顯式型別轉換為不同的類型。

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| To | 要將可列舉物件的元素靜態轉換成的類型 |
| From | 可列舉物件的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| enumerable | const From\& | 包含要轉換之元素的可列舉物件 |

### 返回值

指向新集合的指標，該集合包含類型 **To** 的元素，等價於 **enumerable** 的元素

## System::CastEnumerableTo(const From\&) function

對指定的可列舉物件的元素執行顯式型別轉換為不同的類型。

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| To | 要將可列舉物件的元素靜態轉換成的類型 |
| From | 可列舉物件的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| enumerable | const From\& | 是繼承自具有已定義 get_Count 方法之 Enumerable 物件，且包含要轉換的元素 |

### 返回值

指向新集合的指標，該集合包含類型 **To** 的元素，等價於 **enumerable** 的元素

## 另請參閱

* 類別 [ListPtr](../../system.collections.generic/listptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)