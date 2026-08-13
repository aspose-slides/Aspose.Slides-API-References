---
title: Marshal
second_title: Aspose.Slides for C++ API 레퍼런스
description: 마샬링 구현을 제공합니다. C++ 측에서는 관리 코드가 지원되지 않으므로, 번역된 코드와의 호환성을 위해서만 사용됩니다. 이 타입은 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 14
url: /ko/system.runtime.interopservices/marshal/
---
## Marshal 클래스

관리 구현을 제공합니다. 번역된 코드와의 호환성을 위해서만 사용되며, C++ 측에서는 관리 코드를 지원하지 않습니다. 이 타입은 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class Marshal
```

## 메서드

| Method | Description |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | 관리되지 않는 메모리를 할당합니다. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | 관리되지 않는 메모리를 할당합니다. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 구문을 구현합니다. |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 구문을 구현합니다. |
| static void [Copy](./copy/)(const container\&, int, void *, int) | public static void Copy(char[] source, int startIndex, IntPtr destination, int length) 구문을 구현합니다. |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | public static void Copy(char[] source, int startIndex, IntPtr destination, int length) 구문을 구현합니다. |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | 관리되지 않는 메모리를 해제합니다. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | 관리되지 않는 함수 포인터를 지정된 유형의 delegate로 변환합니다. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | 예외에서 HResult를 가져옵니다. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | 관리되지 않는 null-terminated UTF8 문자열에서 관리된 [String](../../system/string/)를 생성합니다. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | 관리되지 않는 UTF8 문자열에서 관리된 [String](../../system/string/)를 생성합니다. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | 관리되지 않는 null-terminated 문자열에서 관리된 [String](../../system/string/)를 생성합니다. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | 관리되지 않는 문자열에서 관리된 [String](../../system/string/)를 생성합니다. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | 관리되지 않는 null-terminated unicode 문자열에서 관리된 [String](../../system/string/)를 생성합니다. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | 관리되지 않는 unicode 문자열에서 관리된 [String](../../system/string/)를 생성합니다. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | 관리되지 않는 null-terminated UTF8 문자열에서 관리된 [String](../../system/string/)를 생성합니다. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | 관리되지 않는 UTF8 문자열에서 관리된 [String](../../system/string/)를 생성합니다. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | 메모리에서 바이트를 읽습니다. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | 메모리에서 short를 읽습니다. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | 메모리에서 int를 읽습니다. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | 메모리에서 IntPtr를 읽습니다. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | 지정된 보안 문자열의 내용을 관리되지 않는 메모리로 복사하고 ANSI 형식으로 변환합니다. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | 지정된 보안 문자열의 내용을 관리되지 않는 메모리로 복사합니다. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | 지정된 문자열의 내용을 관리되지 않는 메모리로 복사합니다. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | 지정된 문자열의 내용을 관리되지 않는 메모리로 복사하고, 필요한 경우 ANSI 형식으로 변환합니다. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | 지정된 문자열의 내용을 관리되지 않는 메모리로 복사합니다. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | 바이트를 메모리에 씁니다. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | 바이트를 메모리에 씁니다. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | short를 메모리에 씁니다. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | int를 메모리에 씁니다. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | long을 메모리에 씁니다. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | IntPtr를 메모리에 씁니다. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | SecureStringToGlobalAllocAnsi 메서드로 할당된 관리되지 않는 문자열 포인터를 해제합니다. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | SecureStringToGlobalAllocUnicode 메서드로 할당된 관리되지 않는 문자열 포인터를 해제합니다. |
## 참조

* 네임스페이스 [System::Runtime::InteropServices](../)
* 라이브러리 [Aspose.Slides](../../)