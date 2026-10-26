---
title: get_pointer()
second_title: Aspose.Slides for C++ API 參考
description: 取得智慧指標所參考的物件。
type: docs
weight: 2952
url: /zh-hant/system/get_pointer/
---
## System::get_pointer(System::SmartPtr\<T\> const\&) function


取得智慧指標所參考的物件。

```cpp
template<class T> T * System::get_pointer(System::SmartPtr<T> const &x)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 被指向的類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | [System::SmartPtr](../smartptr/)\<T\> const\& | 來源智慧指標。 |

### 回傳值

傳入的智慧指標所參考之物件的原始指標。

## 另請參閱

* 類別 [SmartPtr](../smartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)