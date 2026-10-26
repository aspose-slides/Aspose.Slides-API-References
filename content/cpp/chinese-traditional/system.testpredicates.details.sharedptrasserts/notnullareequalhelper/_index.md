---
title: NotNullAreEqualHelper()
second_title: Aspose.Slides for C++ API 參考
description: 比較抽象集合的相等性。
type: docs
weight: 66
url: /zh-hant/system.testpredicates.details.sharedptrasserts/notnullareequalhelper/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) 函式

比較抽象集合的相等性。

```cpp
template<typename T> bool System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 元素類型。 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 左側值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 右側值。 |

### 回傳值

gtest 風格的斷言結果。

## 另請參閱

* Typedef [SharedPtr](../../system/sharedptr/)
* 類別 [ICollection](../../system.collections.generic/icollection/)
* 命名空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 函式庫 [Aspose.Slides](../../)