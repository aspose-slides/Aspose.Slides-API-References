---
title: operator==()
second_title: Aspose.Slides for C++ API 參考
description: 檢查引用的物件是否為 null.
type: docs
weight: 53
url: /zh-hant/system/weakreference_tmpl_t__end_tmpl/operator_equal_equal/
---
## WeakReference< T >::operator==(std::nullptr_t) const 方法


檢查引用的物件是否為 null。

```cpp
bool System::WeakReference<T>::operator==(std::nullptr_t) const
```


### 返回值

True if referenced object is null, false otherwise.

## WeakReference< T >::operator==(const WeakReference\<T\>\&) const 方法


將引用的物件與另一個 WeakReference 類別實例進行比較。

```cpp
bool System::WeakReference<T>::operator==(const WeakReference<T> &other) const
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [WeakReference](../weakreference/)\<T\>\& | [Object](../../object/) 要比較的物件。 |

### 返回值

True if compared objects reference the same object, false otherwise.

## 另見

* 方法 [WeakReference](../weakreference/)
* 類別 [WeakReference< T >](../)
* 名稱空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)