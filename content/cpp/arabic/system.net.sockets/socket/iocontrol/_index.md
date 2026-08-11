---
title: IOControl()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضبط أوضاع التشغيل منخفضة المستوى للمقبس.
type: docs
weight: 703
url: /ar/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

يضبط أوضاع التشغيل منخفضة المستوى للمقبس.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ioControlCode | **int32_t** | رمز التحكم للعملية التي سيتم تنفيذها. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي تحتوي على بيانات الإدخال. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي تحتوي على بيانات الإخراج. |

### قيمة الإرجاع

عدد البايتات في المعامل **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

يضبط أوضاع التشغيل منخفضة المستوى للمقبس.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | رمز التحكم للعملية التي سيتم تنفيذها. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي تحتوي على بيانات الإدخال. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي تحتوي على بيانات الإخراج. |

### قيمة الإرجاع

عدد البايتات في المعامل **optionOutValue**.

## انظر أيضًا

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)