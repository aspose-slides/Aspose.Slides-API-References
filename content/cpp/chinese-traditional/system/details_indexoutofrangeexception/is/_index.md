---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system/details_indexoutofrangeexception/is/
---
## 細節_IndexOutOfRangeException::Is(const System::TypeInfo\&) const 方法




```cpp
bool System::Details_IndexOutOfRangeException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 結構說明要測試目前物件的類型。 |

### 傳回值

如果物件為具標記類型或其子類別則回傳 True，否則回傳 false。

## 備註

檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 

## 另請參閱

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Details_IndexOutOfRangeException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)