---
title: Ref()
second_title: Aspose.Slides for C++ API 參考
description: 建立對 DynamicWeakPtr 物件的參考。翻譯器在以參照方式傳遞函式參數時使用。
type: docs
weight: 2458
url: /zh-hant/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) 函式


建立對 [DynamicWeakPtr](../dynamicweakptr/) 物件的參考。翻譯器在以參照方式傳遞函式參數時使用。

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Pointee type. |
| trunkMode | Mode of smart pointer itself. |
| weakLeafs | Indexes of template arguments for which SetTemplateWeakPtr method must be called. |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | 欲建立參考的智慧指標。 |

### 返回值

智慧指標參考。

## System::Ref(T\&) 函式


輔助函式，用於取得物件的參考。用於確保在賦值後 [System::DynamicWeakPtr](../dynamicweakptr/) 會更新被參考的物件。

```cpp
template<typename T> T & System::Ref(T &value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Type to create reference to. |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | T\& | 欲建立參考的值。 |

### 返回值

傳遞給此函式的值的參考。

## 另請參閱

* 類別 [DynamicWeakPtr](../dynamicweakptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)