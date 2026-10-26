---
title: StaticCastArray()
second_title: Aspose.Slides for C++ API 參考
description: 執行將指定陣列的元素轉換為不同類型。當 From 為 SmartPtr 物件時覆寫。
type: docs
weight: 2978
url: /zh-hant/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) 函式


執行將指定陣列的元素轉換為不同類型。當 From 為 [SmartPtr](../smartptr/) 物件時覆寫。

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| To | 要將指定陣列的元素轉換成的類型 To |
| From | 要轉換之元素的類型 From |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | 指向包含要轉換之元素之陣列的共享指標 |

### 回傳值

指向新陣列的指標，該陣列包含類型 **To** 的元素，等同於 **from** 的元素

已棄用
:   為了向後相容而加入。請改用 ExplicitCast。

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) 函式


執行將指定陣列的元素轉換為不同類型。當 From 為 Boxable 且 To 為 [Object](../object/)[] 時覆寫。

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| To | 要將指定陣列的元素轉換成的類型 To |
| From | 要轉換之元素的類型 From |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | 指向包含要轉換之元素之陣列的共享指標 |

### 回傳值

指向新陣列的指標，該陣列包含類型 **To** 的元素，等同於 **from** 的元素

已棄用
:   為了向後相容而加入。請改用 ExplicitCast。

## 參見

* 型別別名 [SharedPtr](../sharedptr/)
* 類別 [Array](../array/)
* 類別 [Object](../object/)
* 結構 [IsSmartPtr](../issmartptr/)
* 結構 [IsBoxable](../isboxable/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)