---
title: GetSocketOption()
second_title: مرجع API Aspose.Slides برای C++
description: مقداری را برمی‌گرداند که با نام گزینهٔ مشخص شده مطابقت دارد.
type: docs
weight: 729
url: /fa/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) متد

مقداری را که با نام گزینهٔ مشخص شده مطابقت دارد برمی‌گرداند.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | سطح گزینهٔ سوکت. |
| optionName | [SocketOptionName](../../socketoptionname/) | نام گزینه. |

### مقدار بازگشت

مقداری را که با نام گزینهٔ مشخص شده مطابقت دارد برمی‌گرداند.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) متد

مقداری را که با نام گزینهٔ مشخص شده مطابقت دارد دریافت می‌کند.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | سطح گزینهٔ سوکت. |
| optionName | [SocketOptionName](../../socketoptionname/) | نام گزینه. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | پارامتر خروجی که مقدار متناظر در آن قرار می‌گیرد. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) متد

مقداری را که با نام گزینهٔ مشخص شده مطابقت دارد برمی‌گرداند.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | سطح گزینهٔ سوکت. |
| optionName | [SocketOptionName](../../socketoptionname/) | نام گزینه. |
| optionLength | **int32_t** | طول گزینه. |

### مقدار بازگشت

مقداری را که با نام گزینهٔ مشخص شده مطابقت دارد برمی‌گرداند.

## موارد مرتبط

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)