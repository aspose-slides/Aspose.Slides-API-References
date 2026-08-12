---
title: Marshal
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้การดำเนินการ marshaling เพื่อความเข้ากันได้กับโค้ดที่แปลเท่านั้น เนื่องจากไม่มีการสนับสนุนโค้ดที่จัดการบนฝั่ง C++ นี้เป็นประเภทแบบ static ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ
type: docs
weight: 14
url: /th/system.runtime.interopservices/marshal/
---
## Marshal คลาส

ให้การดำเนินการ marshaling เพื่่อความเข้ากันได้กับโค้ดที่แปลเท่านั้น เนื่องจากไม่มีการสนับสนุนโค้ดที่จัดการบนฝั่ง C++ นี้เป็นประเภทแบบ static ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ

```cpp
class Marshal
```

## เมธอด

| Method | Description |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | จองหน่วยความจำที่ไม่ได้จัดการ. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | จองหน่วยความจำที่ไม่ได้จัดการ. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | ทำตาม semantics ของ public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | ทำตาม semantics ของ public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | ทำตาม public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | ทำตาม public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | ปล่อยหน่วยความจำที่ไม่ได้จัดการ. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | แปลงตัวชี้ฟังก์ชันที่ไม่ได้จัดการเป็น delegate ของประเภทที่ระบุ. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | ดึงค่า HResult จาก exception. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | สร้าง [String](../../system/string/) แบบจัดการจากสตริง UTF8 ที่สิ้นสุดด้วยศูนย์ที่ไม่ได้จัดการ. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | สร้าง [String](../../system/string/) แบบจัดการจากสตริง UTF8 ที่ไม่ได้จัดการ. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | สร้าง [String](../../system/string/) แบบจัดการจากสตริงที่สิ้นสุดด้วยศูนย์ที่ไม่ได้จัดการ. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | สร้าง [String](../../system/string/) แบบจัดการจากสตริงที่ไม่ได้จัดการ. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | สร้าง [String](../../system/string/) แบบจัดการจากสตริงยูนิโค้ดที่สิ้นสุดด้วยศูนย์ที่ไม่ได้จัดการ. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | สร้าง [String](../../system/string/) แบบจัดการจากสตริงยูนิโค้ดที่ไม่ได้จัดการ. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | สร้าง [String](../../system/string/) แบบจัดการจากสตริง UTF8 ที่สิ้นสุดด้วยศูนย์ที่ไม่ได้จัดการ. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | สร้าง [String](../../system/string/) แบบจัดการจากสตริง UTF8 ที่ไม่ได้จัดการ. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | อ่านไบต์จากหน่วยความจำ. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | อ่านค่า short จากหน่วยความจำ. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | อ่านค่า int จากหน่วยความจำ. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | อ่านค่า IntPtr จากหน่วยความจำ. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | คัดลอกเนื้อหาของ secure string ที่ระบุลงในหน่วยความจำที่ไม่ได้จัดการ พร้อมแปลงเป็นรูปแบบ ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | คัดลอกเนื้อหาของ secure string ที่ระบุลงในหน่วยความจำที่ไม่ได้จัดการ. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | คัดลอกเนื้อหาของสตริงที่ระบุลงในหน่วยความจำที่ไม่ได้จัดการ. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | คัดลอกเนื้อหาของสตริงที่ระบุลงในหน่วยความจำที่ไม่ได้จัดการ, แปลงเป็นรูปแบบ ANSI หากจำเป็น. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | คัดลอกเนื้อหาของสตริงที่ระบุลงในหน่วยความจำที่ไม่ได้จัดการ. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | เขียนไบต์ลงในหน่วยความจำ. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | เขียนไบต์ลงในหน่วยความจำ. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | เขียนค่า short ลงในหน่วยความจำ. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | เขียนค่า int ลงในหน่วยความจำ. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | เขียนค่า long ลงในหน่วยความจำ. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | เขียนค่า IntPtr ลงในหน่วยความจำ. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | ปล่อย pointer ของสตริงที่ไม่ได้จัดการที่ถูกจัดสรรโดยวิธี SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | ปล่อย pointer ของสตริงที่ไม่ได้จัดการที่ถูกจัดสรรโดยวิธี SecureStringToGlobalAllocUnicode. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Runtime::InteropServices](../)
* ไลบรารี [Aspose.Slides](../../)