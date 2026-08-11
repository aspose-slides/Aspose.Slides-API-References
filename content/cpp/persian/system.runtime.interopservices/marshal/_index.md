---
title: Marshal
second_title: مرجع API Aspose.Slides برای C++
description: اجرای marshaling را فراهم می‌کند. فقط برای سازگاری با کد ترجمه‌شده استفاده می‌شود، زیرا کد مدیریت‌شده در سمت C++ پشتیبانی نمی‌شود. این یک نوع ایستاتیک بدون سرویس نمونه است. شما نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 14
url: /fa/system.runtime.interopservices/marshal/
---
## کلاس Marshal

اجرای marshaling را فراهم می‌کند. فقط برای سازگاری با کد ترجمه‌شده استفاده می‌شود، زیرا کد مدیریت‌شده در سمت C++ پشتیبانی نمی‌شود. این یک نوع ایستاتیك بدون سرویس نمونه است. شما نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.

```cpp
class Marshal
```

## متدها

| متد | توضیح |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | حافظه غیرمدیریت را تخصیص می‌دهد. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | حافظه غیرمدیریت را تخصیص می‌دهد. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | معنای متد عمومی static void Copy(IntPtr source, byte[] destination, int startIndex, int length) را پیاده‌سازی می‌کند. |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | معنای متد عمومی static void Copy(IntPtr source, byte[] destination, int startIndex, int length) را پیاده‌سازی می‌کند. |
| static void [Copy](./copy/)(const container\&, int, void *, int) | پیاده‌سازی متد عمومی static void Copy(char[] source, int startIndex, IntPtr destination, int length) را انجام می‌دهد. |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | پیاده‌سازی متد عمومی static void Copy(char[] source, int startIndex, IntPtr destination, int length) را انجام می‌دهد. |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | حافظه غیرمدیریت را آزاد می‌کند. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | یک اشاره‌گر تابع غیرمدیریت را به یک delegate از نوع مشخص تبدیل می‌کند. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | HResult را از استثنا دریافت می‌کند. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | یک [String](../../system/string/) مدیریت‌شده را از یک رشته UTF8 صفر-پایان‌دار غیرمدیریت ایجاد می‌کند. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | یک [String](../../system/string/) مدیریت‌شده را از یک رشته UTF8 غیرمدیریت ایجاد می‌کند. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | یک [String](../../system/string/) مدیریت‌شده را از یک رشته صفر-پایان‌دار غیرمدیریت ایجاد می‌کند. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | یک [String](../../system/string/) مدیریت‌شده را از یک رشته غیرمدیریت ایجاد می‌کند. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | یک [String](../../system/string/) مدیریت‌شده را از یک رشته یونیکد صفر-پایان‌دار غیرمدیریت ایجاد می‌کند. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | یک [String](../../system/string/) مدیریت‌شده را از یک رشته یونیکد غیرمدیریت ایجاد می‌کند. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | یک [String](../../system/string/) مدیریت‌شده را از یک رشته UTF8 صفر-پایان‌دار غیرمدیریت ایجاد می‌کند. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | یک [String](../../system/string/) مدیریت‌شده را از یک رشته UTF8 غیرمدیریت ایجاد می‌کند. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | یک بایت را از حافظه می‌خواند. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | یک short را از حافظه می‌خواند. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | یک int را از حافظه می‌خواند. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | یک IntPtr را از حافظه می‌خواند. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | محتویات رشته امن مشخص شده را به حافظه غیرمدیریت کپی می‌کند و به فرمت ANSI تبدیل می‌نماید. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | محتویات رشته امن مشخص شده را به حافظه غیرمدیریت کپی می‌کند. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | محتویات یک رشتهٔ مشخص را به حافظه غیرمدیریت کپی می‌کند. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | محتویات یک رشتهٔ مشخص را به حافظه غیرمدیریت کپی می‌کند و در صورت نیاز به فرمت ANSI تبدیل می‌کند. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | محتویات یک رشتهٔ مشخص را به حافظه غیرمدیریت کپی می‌کند. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | یک بایت را در حافظه می‌نویسد. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | یک بایت را در حافظه می‌نویسد. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | یک short را در حافظه می‌نویسد. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | یک int را در حافظه می‌نویسد. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | یک long را در حافظه می‌نویسد. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | یک IntPtr را در حافظه می‌نویسد. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | اشاره‌گر رشته غیرمدیریت که با متد SecureStringToGlobalAllocAnsi تخصیص یافته بود را آزاد می‌کند. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | اشاره‌گر رشته غیرمدیریت که با متد SecureStringToGlobalAllocUnicode تخصیص یافته بود را آزاد می‌کند. |

## مراجع

* فضای‌نام [System::Runtime::InteropServices](../)
* کتابخانه [Aspose.Slides](../../)