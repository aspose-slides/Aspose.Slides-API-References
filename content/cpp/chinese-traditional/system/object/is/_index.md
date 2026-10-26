---
title: Is()
second_title: Aspose.Slides C++ API 參考文件
description: 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 的 'is' 運算子。
type: docs
weight: 222
url: /zh-hant/system/object/is/
---
## Object::Is(const TypeInfo\&) const 方法


Check if object represents an instance of type described by targetType. Analog of C# 'is' operator.

```cpp
virtual bool System::Object::Is(const TypeInfo &targetType) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetType | const [TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 結構，描述要測試目前物件所屬的型別。 |

### 返回值

如果物件屬於標記的型別或其子類別則返回 True，否則返回 false。

## 另請參閱

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Object](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)