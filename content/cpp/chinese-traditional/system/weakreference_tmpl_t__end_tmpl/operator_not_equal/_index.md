---
title: operator!=()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查參考的物件是否為 null.
type: docs
weight: 66
url: /zh-hant/system/weakreference_tmpl_t__end_tmpl/operator_not_equal/
---
## WeakReference< T >::operator!=(std::nullptr_t) const method

檢查參考的物件是否為 null。

```cpp
bool System::WeakReference<T>::operator!=(std::nullptr_t) const
```

### 回傳值

若參考的物件不為 null，則回傳 true，否則回傳 false。

## WeakReference< T >::operator!=(const WeakReference\<T\>\&) const method

比較參考的物件與另一個 WeakReference 類別的實例。

```cpp
bool System::WeakReference<T>::operator!=(const WeakReference<T> &other) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const [WeakReference](../weakreference/)\<T\>\& | [Object](../../object/) 比較至。 |

### 回傳值

若比較的物件參考不同的物件，則回傳 true，若物件相同則回傳 false。

## 另見

* 方法 [WeakReference](../weakreference/)
* 類別 [WeakReference< T >](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)