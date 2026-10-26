---
title: WeakReference()
second_title: Aspose.Slides for C++ API 參考文件
description: 預設建構子。
type: docs
weight: 1
url: /zh-hant/system/weakreference_tmpl_t__end_tmpl/weakreference/
---
## WeakReference< T >::WeakReference() 方法

預設建構函式。

```cpp
System::WeakReference<T>::WeakReference()
```

## WeakReference< T >::WeakReference(std::nullptr_t) 方法

從 nullptr 的建構函式。

```cpp
System::WeakReference<T>::WeakReference(std::nullptr_t)
```

## WeakReference< T >::WeakReference(const SmartPtr\<T\>\&) 方法

初始化 WeakReference 類別的新執行個體，參照指定的物件。

```cpp
System::WeakReference<T>::WeakReference(const SmartPtr<T> &data)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<T\>\& | [Object](../../object/) 要儲存。 |

## WeakReference< T >::WeakReference(const SmartPtr\<T\>\&, bool) 方法

初始化 WeakReference 類別的新執行個體，參照指定的物件。

```cpp
System::WeakReference<T>::WeakReference(const SmartPtr<T> &data, bool trackResurrection)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<T\>\& | [Object](../../object/) 要儲存。 |
| trackResurrection | **bool** | 已忽略。 |

## 另請參閱

* 類別 [WeakReference< T >](../)
* 類別 [SmartPtr](../../smartptr/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)