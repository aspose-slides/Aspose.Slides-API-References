---
title: Format()
second_title: Aspose.Slides C++ API 参考
description: 返回使用指定格式表示的当前对象所代表的值的字符串形式。
type: docs
weight: 1
url: /zh/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) 方法

返回当前对象使用指定格式表示的值的字符串形式。

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| format | [System::String](../../string/) | 字符串格式 |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | 要格式化的对象 |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 提供格式化信息的对象 |

### 返回值

返回根据 **format** 和 **formatProvider** 指定的格式对 **arg** 进行格式化后的字符串表示。

## 参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [Object](../../object/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [ICustomFormatter](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)