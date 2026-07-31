---
title: Marshal
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan implementasi marshalling. Hanya untuk kompatibilitas dengan kode yang diterjemahkan, karena tidak ada kode terkelola yang didukung di sisi C++. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh membuat instance darinya dengan cara apa pun.
type: docs
weight: 14
url: /id/system.runtime.interopservices/marshal/
---
## Marshal kelas

Menyediakan implementasi marshalling. Hanya untuk kompatibilitas dengan kode yang diterjemahkan, karena tidak ada kode terkelola yang didukung di sisi C++. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh membuat instance darinya dengan cara apa pun.

```cpp
class Marshal
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Mengalokasikan memori yang tidak dikelola. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Mengalokasikan memori yang tidak dikelola. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Mengimplementasikan semantik public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Mengimplementasikan semantik public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Mengimplementasikan semantik public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Mengimplementasikan semantik public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Membebaskan memori yang tidak dikelola. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Mengonversi pointer fungsi yang tidak dikelola menjadi delegasi dengan tipe yang ditentukan. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Mendapatkan HResult dari pengecualian. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Membuat [String](../../system/string/) terkelola dari string UTF8 berakhiran nol yang tidak dikelola. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Membuat [String](../../system/string/) terkelola dari string UTF8 yang tidak dikelola. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Membuat [String](../../system/string/) terkelola dari string berakhiran nol yang tidak dikelola. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Membuat [String](../../system/string/) terkelola dari string yang tidak dikelola. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Membuat [String](../../system/string/) terkelola dari string unicode berakhiran nol yang tidak dikelola. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Membuat [String](../../system/string/) terkelola dari string unicode yang tidak dikelola. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Membuat [String](../../system/string/) terkelola dari string UTF8 berakhiran nol yang tidak dikelola. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Membuat [String](../../system/string/) terkelola dari string UTF8 yang tidak dikelola. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Membaca byte dari memori. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Membaca short dari memori. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Membaca int dari memori. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Membaca IntPtr dari memori. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Menyalin isi secure string yang ditentukan ke memori yang tidak dikelola, mengonversinya ke format ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Menyalin isi secure string yang ditentukan ke memori yang tidak dikelola. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Menyalin isi string yang ditentukan ke memori yang tidak dikelola. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Menyalin isi string yang ditentukan ke memori yang tidak dikelola, mengonversinya ke format ANSI jika diperlukan. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Menyalin isi string yang ditentukan ke memori yang tidak dikelola. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Menulis byte ke memori. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Menulis byte ke memori. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Menulis short ke memori. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Menulis int ke memori. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Menulis long ke memori. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Menulis IntPtr ke memori. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Membebaskan pointer string yang tidak dikelola yang dialokasikan menggunakan metode SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Membebaskan pointer string yang tidak dikelola yang dialokasikan menggunakan metode SecureStringToGlobalAllocUnicode. |
## Lihat Juga

* Ruang Nama [System::Runtime::InteropServices](../)
* Pustaka [Aspose.Slides](../../)