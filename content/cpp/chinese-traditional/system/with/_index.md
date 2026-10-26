---
title: With()
second_title: Aspose.Slides for C++ API 參考文件
description: 複製參考記錄並將初始化函式子套用至該記錄。
type: docs
weight: 2614
url: /zh-hant/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) 函式


複製參考記錄並將初始化函式子套用至它。

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | Record type to clone. |
| A | Initialization functor type. |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Shared pointer to the object to clone and initialize. |
| initializer | const A\& | Initialization functor being applied to record clone. |

### 傳回值

Shared pointer to cloned record.

## System::With(const T\&, const A\&) 函式


複製結構記錄並將初始化函式子套用至它。

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | Record type to copy. |
| A | Initialization functor type. |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| record | const T\& | Record to copy and initialize. |
| initializer | const A\& | Initialization functor being applied to record copy. |

### 傳回值

Copied record.

## 另請參閱

* Typedef [SharedPtr](../sharedptr/)
* 命名空間 [System](../)
* Library [Aspose.Slides](../../)