---
title: NetworkStream()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مثلاً جديدًا.
type: docs
weight: 170
url: /ar/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) منشئ

ينشئ مثلاً جديدًا.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | المقبس socket الذي يُستخدم لإرسال واستقبال البيانات. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) منشئ

ينشئ مثلاً جديدًا.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | المقبس socket الذي يُستخدم لإرسال واستقبال البيانات. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | يحدد نوع الوصول الممنوح للمعامل access عبر المقبس المحدد. |
| ownsSocket | **bool** | قيمة تشير إلى ما إذا كانت النسخة الحالية تأخذ ملكية المقبس المحدد عندما تكون القيمة true. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) منشئ

ينشئ مثلاً جديدًا.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | المقبس socket الذي يُستخدم لإرسال واستقبال البيانات. |
| ownsSocket | **bool** | قيمة تشير إلى ما إذا كانت النسخة الحالية تأخذ ملكية المقبس المحدد عندما تكون القيمة true. |

## انظر أيضًا

* تعداد [FileAccess](../../../system.io/fileaccess/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Socket](../../socket/)
* فئة [NetworkStream](../)
* مساحة اسم [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)