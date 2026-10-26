---
title: DynamicCastArray()
second_title: Aspose.Slides C++ API 參考文件
description: 執行將指定陣列的元素轉換為不同類型。
type: docs
weight: 2991
url: /zh-hant/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) 函式


執行將指定陣列的元素轉換為不同類型的操作。

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| To | 要將指定陣列的元素轉換為的類型 |
| From | 要轉換的陣列元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | 指向包含要轉換之元素的陣列的共享指標 |

### 返回值

指向新陣列的指標，該陣列包含類型 **To** 的元素，與 **from** 的元素等價

已棄用
:   為了向後相容性而新增。請改用 ExplicitCast。

## 另請參閱

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)