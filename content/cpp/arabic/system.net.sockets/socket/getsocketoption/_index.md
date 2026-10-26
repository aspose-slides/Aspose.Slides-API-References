---
title: GetSocketOption()
second_title: Aspose.Slides لمرجع API لـ C++
description: يرجع القيمة التي تتطابق مع اسم الخيار المحدد.
type: docs
weight: 729
url: /ar/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) طريقة

يرجع القيمة التي تتطابق مع اسم الخيار المحدد.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | مستوى خيار المقبس. |
| optionName | [SocketOptionName](../../socketoptionname/) | اسم الخيار. |

### قيمة الإرجاع

القيمة التي تتطابق مع اسم الخيار المحدد.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) طريقة

يحصل على القيمة التي تتطابق مع اسم الخيار المحدد.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | مستوى خيار المقبس. |
| optionName | [SocketOptionName](../../socketoptionname/) | اسم الخيار. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | معامل الإخراج حيث سيتم تعيين القيمة المقابلة. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) طريقة

يرجع القيمة التي تتطابق مع اسم الخيار المحدد.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | مستوى خيار المقبس. |
| optionName | [SocketOptionName](../../socketoptionname/) | اسم الخيار. |
| optionLength | **int32_t** | طول الخيار. |

### قيمة الإرجاع

القيمة التي تتطابق مع اسم الخيار المحدد.

## انظر أيضًا

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [Object](../../../system/object/)
* فئة [Socket](../)
* نطاق [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)