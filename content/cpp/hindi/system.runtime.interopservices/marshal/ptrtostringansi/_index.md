---
title: PtrToStringAnsi()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अप्रबंधित zero-terminated UTF8-string से एक प्रबंधित String बनाता है।
type: docs
weight: 274
url: /hi/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) मेथड

एक unmanaged zero-terminated UTF8-string से एक managed [String](../../../system/string/) बनाता है।

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ptr | IntPtr | अप्रबंधित स्ट्रिंग के लिए पॉइंटर। |

### वापसी मान

एक managed स्ट्रिंग।

## Marshal::PtrToStringAnsi(IntPtr, int) मेथड

एक unmanaged UTF8-string से एक managed [String](../../../system/string/) बनाता है।

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ptr | IntPtr | अप्रबंधित स्ट्रिंग के लिए पॉइंटर। |
| length | int | अप्रबंधित स्ट्रिंग की लंबाई। |

### वापसी मान

एक managed स्ट्रिंग।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [Marshal](../)
* नेमस्पेस [System::Runtime::InteropServices](../../)
* लाइब्रेरी [Aspose.Slides](../../../)