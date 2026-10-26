---
title: MakeObject()
second_title: Aspose.Slides for C++ API 參考文件
description: 在堆上建立物件並回傳其 shared 指標。
type: docs
weight: 2887
url: /zh-hant/system/makeobject/
---
## System::MakeObject(Args\&&...) 函式

在堆上建立物件並回傳 shared 指標。

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 要實例化的類別。 |
| Args | 建構函式參數的型別。 |

### 引數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| args | Args\&&... | 建構函式參數。 |

### 傳回值

[SmartPtr](../smartptr/) 到新建立的物件，始終以共享模式。

## System::MakeObject(Args\&&...) 函式

在堆上建立物件並回傳 shared 指標。

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [SmartPtr](../smartptr/) 到類別以實例化。 |
| Args | 建構函式參數的型別。 |

### 引數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| args | Args\&&... | 建構函式參數。 |

### 傳回值

[SmartPtr](../smartptr/) 到新建立的物件，始終以共享模式。

## 另請參閱

* 類別 [SmartPtr](../smartptr/)
* 結構 [IsSmartPtr](../issmartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)