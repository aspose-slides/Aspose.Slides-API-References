---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system/details_notsupportedexception/is/
---
## 詳細_NotSupportedException::Is(const System::TypeInfo\&) const 方法




```cpp
bool System::Details_NotSupportedException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 結構描述要測試當前對象的類型。 |

### 返回值

如果對象是標記類型或其子類則返回 true，否則返回 false。

## 備註

檢查對象是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。

## 另請參閱

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Details_NotSupportedException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)