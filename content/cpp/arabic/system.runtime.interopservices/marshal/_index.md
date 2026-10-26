---
title: Marshal
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يوفّر تنفيذ عملية الـ marshalling. يُستخدم فقط لتوافق الشيفرة المترجمة، حيث لا يُدعم أي كود مُدار على جانب C++. هذا نوع ثابت بدون خدمات مثيل. لا ينبغي لك أبداً إنشاء مثيلات منه بأي وسيلة.
type: docs
weight: 14
url: /ar/system.runtime.interopservices/marshal/
---
## فئة Marshal

Provides marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Marshal
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | يخصّص الذاكرة غير المُدارة. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | يخصّص الذاكرة غير المُدارة. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | ينفّذ دلالة الدالة العامة الثابتة void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | ينفّذ دلالة الدالة العامة الثابتة void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | ينفّذ دلالة الدالة العامة الثابتة void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | ينفّذ دلالة الدالة العامة الثابتة void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | يفرّ الذاكرة غير المُدارة. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | يحوّل مؤشر دالة غير مُدارة إلى موزّع من نوع محدد. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | يحصل على HResult من الاستثناء. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | ينشئ [String](../../system/string/) مُدارًا من سلسلة UTF8 منتهيّة بالصفر غير مُدارة. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | ينشئ [String](../../system/string/) مُدارًا من سلسلة UTF8 غير مُدارة. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | ينشئ [String](../../system/string/) مُدارًا من سلسلة غير مُدارة منتهيّة بالصفر. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | ينشئ [String](../../system/string/) مُدارًا من سلسلة غير مُدارة. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | ينشئ [String](../../system/string/) مُدارًا من سلسلة Unicode غير مُدارة منتهيّة بالصفر. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | ينشئ [String](../../system/string/) مُدارًا من سلسلة Unicode غير مُدارة. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | ينشئ [String](../../system/string/) مُدارًا من سلسلة UTF8 غير مُدارة منتهيّة بالصفر. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | ينشئ [String](../../system/string/) مُدارًا من سلسلة UTF8 غير مُدارة. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | يقرأ بايت من الذاكرة. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | يقرأ قيمة قصيرة (short) من الذاكرة. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | يقرأ قيمة int من الذاكرة. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | يقرأ IntPtr من الذاكرة. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | ينسخ محتويات السلسلة الآمنة المحددة إلى الذاكرة غير المُدارة، مع التحويل إلى تنسيق ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | ينسخ محتويات السلسلة الآمنة المحددة إلى الذاكرة غير المُدارة. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | ينسخ محتويات السلسلة المحددة إلى الذاكرة غير المُدارة. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | ينسخ محتويات السلسلة المحددة إلى الذاكرة غير المُدارة، مع التحويل إلى تنسيق ANSI إذا لزم الأمر. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | ينسخ محتويات السلسلة المحددة إلى الذاكرة غير المُدارة. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | يكتب بايت إلى الذاكرة. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | يكتب بايت إلى الذاكرة. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | يكتب قيمة قصيرة (short) إلى الذاكرة. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | يكتب قيمة int إلى الذاكرة. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | يكتب قيمة long إلى الذاكرة. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | يكتب IntPtr إلى الذاكرة. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | يفرّ مؤشّر سلسلة غير مُدارة تم تخصيصه باستخدام طريقة SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | يفرّ مؤشّر سلسلة غير مُدارة تم تخصيصه باستخدام طريقة SecureStringToGlobalAllocUnicode. |

## أنظر أيضًا

* النطاق [System::Runtime::InteropServices](../)
* المكتبة [Aspose.Slides](../../)