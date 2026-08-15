---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system.runtime.serialization/details_serializationexception/is/
---
## 細節_SerializationException::Is(const System::TypeInfo\&) const 方法




```cpp
bool System::Runtime::Serialization::Details_SerializationException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 結構，描述用於測試當前物件的類型。 |

### 回傳值

True if object is of tagged type or its subclass, false otherwise.

## 備註

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 

## 另見

* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [Details_SerializationException](../)
* 命名空間 [System::Runtime::Serialization](../../)
* 程式庫 [Aspose.Slides](../../../)