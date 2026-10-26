---
title: Marshal
second_title: Aspose.Slides for C++ API Referansı
description: Marshalling uygulamasını sağlar. Yalnızca çevrilmiş kodla uyumluluk için, C++ tarafında yönetilen kod desteklenmediği için. Bu, örnek hizmeti olmayan statik bir türdür. Onu hiçbir şekilde örneklememeniz gerekir.
type: docs
weight: 14
url: /tr/system.runtime.interopservices/marshal/
---
## Marshal sınıfı

Marshalling uygulamasını sağlar. Yalnızca çevrilmiş kod ile uyumluluk için, C++ tarafında yönetilen kod desteklenmediği için. Bu, örnek hizmeti olmayan statik bir türdür. Onun hiçbir örneğini hiçbir şekilde oluşturmayınız.

```cpp
class Marshal
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Yönetilmeyen belleği ayırır. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Yönetilmeyen belleği ayırır. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantiğini uygular. |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantiğini uygular. |
| static void [Copy](./copy/)(const container\&, int, void *, int) | public static void Copy(char[] source, int startIndex, IntPtr destination, int length) semantiğini uygular. |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | public static void Copy(char[] source, int startIndex, IntPtr destination, int length) semantiğini uygular. |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Yönetilmeyen belleği serbest bırakır. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Yönetilmeyen fonksiyon işaretçisini belirtilen tipte bir delegeye dönüştürür. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | İstisnadan HResult alır. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Yönetilmeyen sıfır sonlu UTF8 dizesinden yönetilen [String](../../system/string/) oluşturur. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Yönetilmeyen UTF8 dizesinden yönetilen [String](../../system/string/) oluşturur. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Yönetilmeyen sıfır sonlu dizeden yönetilen [String](../../system/string/) oluşturur. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Yönetilmeyen dizeden yönetilen [String](../../system/string/) oluşturur. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Yönetilmeyen sıfır sonlu Unicode dizesinden yönetilen [String](../../system/string/) oluşturur. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Yönetilmeyen Unicode dizeden yönetilen [String](../../system/string/) oluşturur. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Yönetilmeyen sıfır sonlu UTF8 dizesinden yönetilen [String](../../system/string/) oluşturur. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Yönetilmeyen UTF8 dizeden yönetilen [String](../../system/string/) oluşturur. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Bellekten bir bayt okur. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Bellekten bir short okur. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Bellekten bir int okur. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Bellekten bir IntPtr okur. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Belirtilen güvenli dize içeriğini yönetilmeyen belleğe kopyalar, ANSI formatına dönüştürür. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Belirtilen güvenli dize içeriğini yönetilmeyen belleğe kopyalar. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Belirtilen dize içeriğini yönetilmeyen belleğe kopyalar. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Belirtilen dize içeriğini yönetilmeyen belleğe kopyalar, gerekirse ANSI formatına dönüştürür. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Belirtilen dize içeriğini yönetilmeyen belleğe kopyalar. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Belleğe bir bayt yazar. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Belleğe bir bayt yazar. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Belleğe bir short yazar. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Belleğe bir int yazar. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Belleğe bir long yazar. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Belleğe bir IntPtr yazar. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | SecureStringToGlobalAllocAnsi yöntemiyle ayrılan yönetilmeyen dize işaretçisini serbest bırakır. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | SecureStringToGlobalAllocUnicode yöntemiyle ayrılan yönetilmeyen dize işaretçisini serbest bırakır. |

## İlgili

* Ad alanı [System::Runtime::InteropServices](../)
* Kütüphane [Aspose.Slides](../../)