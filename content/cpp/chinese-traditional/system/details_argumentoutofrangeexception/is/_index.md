---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system/details_argumentoutofrangeexception/is/
---
## 詳細_ArgumentOutOfRangeException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_ArgumentOutOfRangeException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 結構描述要測試當前物件的類型。 |

### 回傳值

如果物件是已標記的類型或其子類別則為 True，否則為 false。

## 備註

檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。

## 另見

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Details_ArgumentOutOfRangeException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)