---
title: Is()
second_title: Aspose.Slides for C++ API 參考手冊
description: 
type: docs
weight: 27
url: /zh-hant/system.io/details_endofstreamexception/is/
---
## 詳細資訊_EndOfStreamException::Is(const System::TypeInfo\&) const method




```cpp
bool System::IO::Details_EndOfStreamException::Is(const System::TypeInfo &target) const override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 結構描述要測試當前物件所屬的類型。 |

### 回傳值

如果物件是指定的類型或其子類別則返回 true，否則返回 false。

## 備註

檢查物件是否為 targetType 描述的類型的實例。相當於 C# 的 'is' 運算子。

## 另請參閱

* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [Details_EndOfStreamException](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)