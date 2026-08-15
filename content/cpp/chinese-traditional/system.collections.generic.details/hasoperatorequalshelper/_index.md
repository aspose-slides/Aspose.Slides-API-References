---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides for C++ API 參考
description: 輔助函式，用於判斷特定類別是否具備 operator ==.
type: docs
weight: 235
url: /zh-hant/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) function

輔助函式，用於判斷特定類別是否具備 operator ==。

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| T | 要檢查的類型。 |
| Dummy | 用於 SFINAE 魔術的虛擬參數。 |

### 返回值

如果存在 operator ==，則返回 std::true_type 的值；否則返回 false。

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) function

輔助函式，用於判斷特定類別是否具備 operator ==。

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### 返回值

如果存在 operator ==，則返回 std::true_type 的值；否則返回 false。

## 另請參閱

* 命名空間 [System::Collections::Generic::Details](../)
* 函式庫 [Aspose.Slides](../../)