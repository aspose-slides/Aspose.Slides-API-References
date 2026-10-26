---
title: WeakReference()
second_title: Aspose.Slides C++ API 參考
description: 預設建構函式。
type: docs
weight: 1
url: /zh-hant/system/weakreference_tmpl_end_tmpl/weakreference/
---
## WeakReference<>::WeakReference() 方法

預設建構函式。

```cpp
System::WeakReference<>::WeakReference()
```

## WeakReference<>::WeakReference(std::nullptr_t) 方法

從 nullptr 的建構函式。

```cpp
System::WeakReference<>::WeakReference(std::nullptr_t)
```

## WeakReference<>::WeakReference(const SmartPtr\<Object\>\&) 方法

初始化 WeakReference 類別的新實例，引用指定的物件。

```cpp
System::WeakReference<>::WeakReference(const SmartPtr<Object> &data)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | 要儲存的 [Object](../../object/)。 |

## WeakReference<>::WeakReference(const SmartPtr\<Object\>\&, bool) 方法

初始化 WeakReference 類別的新實例，引用指定的物件。

```cpp
System::WeakReference<>::WeakReference(const SmartPtr<Object> &data, bool trackResurrection)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | 要儲存的 [Object](../../object/)。 |
| trackResurrection | **bool** | 忽略。 |

## 參見

* 類別 [WeakReference<>](../)
* 類別 [SmartPtr](../../smartptr/)
* 類別 [Object](../../object/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)