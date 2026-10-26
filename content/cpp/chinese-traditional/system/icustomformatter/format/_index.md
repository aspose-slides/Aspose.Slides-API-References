---
title: Format()
second_title: Aspose.Slides for C++ API 參考
description: 傳回以指定格式表示目前物件所代表之值的字串表示形式。
type: docs
weight: 1
url: /zh-hant/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) method


傳回以指定格式表示目前物件所代表之值的字串表示形式。

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | [System::String](../../string/) | 字串格式 |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | 要格式化的物件 |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 提供格式資訊的物件 |

### 傳回值

根據 **format** 與 **formatProvider** 所指定的格式，**arg** 的字串表示形式

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [Object](../../object/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [ICustomFormatter](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)