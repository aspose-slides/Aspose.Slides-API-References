---
title: "System::Net::Sockets"
second_title: مرجع API Aspose.Slides للـ C++
description: 
type: docs
weight: 729
url: /ar/system.net.sockets/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | يمثل الاستثناء الذي يُرمي عندما يحدث خطأ في المقبس. لا تقم بإنشاء مثيلات من هذه الفئة يدويًا. استخدم فئة SocketException بدلاً من ذلك. لا تقم بلف مثيلات فئة SocketException في [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | يمثل معلومات حول الحزمة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، لأنه سيتسبب في أخطاء وقت التشغيل و/أو أعطال التحقق. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [LingerOption](./lingeroption/) | يحدد ما إذا كان المقبس سيبقى متصلًا بعد استدعاء الدالة Close() أو طرقي Close(). كما يحدد الفترة التي سيبقى فيها المقبس متصلًا إذا استمر إرسال البيانات. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، لأنه سيتسبب في أخطاء وقت التشغيل و/أو أعطال التحقق. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [NetworkStream](./networkstream/) | يوفر تدفق البيانات الأساسي للوصول إلى الشبكة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، لأنه سيتسبب في أخطاء وقت التشغيل و/أو أعطال التحقق. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [Socket](./socket/) | الفئة [Socket](./socket/) تنفّذ واجهة Berkeley sockets. |
| [TcpClient](./tcpclient/) | يمثل عميلًا لخدمات الشبكة TCP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، لأنه سيتسبب في أخطاء وقت التشغيل و/أو أعطال التحقق. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [TcpListener](./tcplistener/) | يمثل مستمعًا لخدمات الشبكة TCP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، فهو سيتسبب في أخطاء وقت التشغيل و/أو أعطال التحقق. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [UdpClient](./udpclient/) | يوفر خدمات شبكة بروتوكول بيانات المستخدم (UDP). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، فهو سيتسبب في أخطاء وقت التشغيل و/أو أعطال التحقق. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |

## الدوال

| الدالة | الوصف |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## التعدادات

| التعداد | الوصف |
| --- | --- |
| [SocketType](./sockettype/) | يعدّد أنواع المقبس. |
| [AddressFamily](./addressfamily/) | يعدّد عائلات العناوين. |
| [IOControlCode](./iocontrolcode/) | يعدّد رموز التحكم [IO](../system.io/). |
| [ProtocolFamily](./protocolfamily/) | يعدّد عائلات البروتوكول. |
| [ProtocolType](./protocoltype/) | يعدّد أنواع البروتوكول. |
| [SelectMode](./selectmode/) | يحدد الوضع لاستطلاع حالة المقبس. |
| [SocketError](./socketerror/) | يعدّد أنواع أخطاء المقبس. |
| [SocketFlags](./socketflags/) | يوفر قيم ثابتة لرسائل المقبس. |
| [SocketOptionLevel](./socketoptionlevel/) | يحدد مستويات خيار المقبس للفئة '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | يحدد أسماء خيار المقبس للفئة [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | يحدد الثوابت المستخدمة بواسطة طريقة [Socket.Shutdown](./socket/shutdown/). |

## تعريفات النوع

| تعريف نوع | الوصف |
| --- | --- |
| [SocketException](./socketexception/) |  |