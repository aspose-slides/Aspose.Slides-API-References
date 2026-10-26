---
title: Is()
second_title: Aspose.Slides for C++ API 參考手冊
description: 
type: docs
weight: 27
url: /zh-hant/system/details_argumentexception/is/
---
## Details_ArgumentException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_ArgumentException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 結構，描述要測試當前物件的類型。 |

### 回傳值

True if object is of tagged type or its subclass, false otherwise.

## 備註

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 

## 另請參閱

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Details_ArgumentException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)