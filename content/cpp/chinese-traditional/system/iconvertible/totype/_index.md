---
title: ToType()
second_title: Aspose.Slides for C++ API 參考文件
description: "將此實例的值轉換為指定 System::Type 的 System::Object，該物件具有等效的值，並使用指定的文化特定格式資訊。"
type: docs
weight: 209
url: /zh-hant/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) 方法

將此實例的值轉換為指定 System::Type 的 [System::Object](../../object/)，其具有等價的值，並使用指定的文化特定格式資訊。

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | 此實例的值將被轉換成的 System::Type。 |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 提供文化特定格式資訊的 [System::IFormatProvider](../../iformatprovider/) 介面實作。 |

### 返回值

一個類型為 conversionType、其值等同於此實例值的 [System::Object](../../object/) 例項。

## 另見

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [Object](../../object/)
* 類別 [TypeInfo](../../typeinfo/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [IConvertible](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)