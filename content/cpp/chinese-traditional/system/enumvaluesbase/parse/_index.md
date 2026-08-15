---
title: Parse()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回一個物件，該物件表示具指定名稱之指定列舉類型的列舉常數值。
type: docs
weight: 27
url: /zh-hant/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) 方法

返回一個物件，該物件表示指定列舉類型中具有指定名稱的列舉常數的值。

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 代表要返回之列舉值類型的 [TypeInfo](../../typeinfo/) 物件 |
| str | const [String](../../string/)\& | 列舉常數的名稱 |
| ignoreCase | **bool** | 指定在解讀列舉常數名稱時是否忽略大小寫 |

### 返回值

一個物件，表示 **str** 所指定名稱的列舉常數的值。

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)