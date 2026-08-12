---
title: Marshal
second_title: Aspose.Slides for C++ API संदर्भ
description: मार्शलिंग कार्यान्वयन प्रदान करता है। केवल अनूदित कोड की संगतता के लिए, क्योंकि C++ पक्ष पर कोई प्रबंधित कोड समर्थित नहीं है। यह एक स्थैतिक प्रकार है जिसके पास कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इसे किसी भी माध्यम से कभी भी इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 14
url: /hi/system.runtime.interopservices/marshal/
---
## Marshal class


मार्शलिंग कार्यान्वयन प्रदान करता है। केवल अनूदित कोड के साथ संगतता के लिए, क्योंकि C++ पक्ष पर कोई प्रबंधित कोड समर्थित नहीं है। यह एक static प्रकार है जिसके पास कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इसे किसी भी प्रकार से कभी भी इंस्टेंस नहीं बनाना चाहिए।

```cpp
class Marshal
```

## Methods

| मेथड | विवरण |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | अप्रबंधित मेमोरी आवंटित करता है। |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | अप्रबंधित मेमोरी आवंटित करता है। |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) सेमांटिक्स को लागू करता है। |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) सेमांटिक्स को लागू करता है। |
| static void [Copy](./copy/)(const container\&, int, void *, int) | public static void Copy(char[] source, int startIndex, IntPtr destination, int length) को लागू करता है। |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | public static void Copy(char[] source, int startIndex, IntPtr destination, int length) को लागू करता है। |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | अप्रबंधित मेमोरी को मुक्त करता है। |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | एक अप्रबंधित फ़ंक्शन पॉइंटर को निर्दिष्ट प्रकार के डेलीगेट में परिवर्तित करता है। |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | एक्सेप्शन से HResult प्राप्त करता है। |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | एक अप्रबंधित शून्य-समाप्त UTF8-स्ट्रिंग से एक प्रबंधित [String](../../system/string/) बनाता है। |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | एक अप्रबंधित UTF8-स्ट्रिंग से एक प्रबंधित [String](../../system/string/) बनाता है। |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | एक अप्रबंधित शून्य-समाप्त स्ट्रिंग से एक प्रबंधित [String](../../system/string/) बनाता है। |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | एक अप्रबंधित स्ट्रिंग से एक प्रबंधित [String](../../system/string/) बनाता है। |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | एक अप्रबंधित शून्य-समाप्त यूनिकोड स्ट्रिंग से एक प्रबंधित [String](../../system/string/) बनाता है। |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | एक अप्रबंधित यूनिकोड स्ट्रिंग से एक प्रबंधित [String](../../system/string/) बनाता है। |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | एक अप्रबंधित शून्य-समाप्त UTF8-स्ट्रिंग से एक प्रबंधित [String](../../system/string/) बनाता है। |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | एक अप्रबंधित UTF8-स्ट्रिंग से एक प्रबंधित [String](../../system/string/) बनाता है। |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | मेमोरी से बाइट पढ़ता है। |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | मेमोरी से शॉर्ट पढ़ता है। |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | मेमोरी से इंट पढ़ता है। |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | मेमोरी से IntPtr पढ़ता है। |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | निर्दिष्ट सुरक्षित स्ट्रिंग की सामग्री को अप्रबंधित मेमोरी में कॉपी करता है, ANSI फ़ॉर्मेट में परिवर्तित करता है। |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | निर्दिष्ट सुरक्षित स्ट्रिंग की सामग्री को अप्रबंधित मेमोरी में कॉपी करता है। |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रिंग की सामग्री को अप्रबंधित मेमोरी में कॉपी करता है। |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रिंग की सामग्री को अप्रबंधित मेमोरी में कॉपी करता है, आवश्यक होने पर ANSI फ़ॉर्मेट में परिवर्तित करता है। |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रिंग की सामग्री को अप्रबंधित मेमोरी में कॉपी करता है। |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | मेमोरी में बाइट लिखता है। |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | मेमोरी में बाइट लिखता है। |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | मेमोरी में शॉर्ट लिखता है। |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | मेमोरी में इंट लिखता है। |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | मेमोरी में लॉन्ग लिखता है। |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | मेमोरी में IntPtr लिखता है। |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | SecureStringToGlobalAllocAnsi मेथड का उपयोग करके आवंटित अप्रबंधित स्ट्रिंग पॉइंटर को मुक्त करता है। |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | SecureStringToGlobalAllocUnicode मेथड का उपयोग करके आवंटित अप्रबंधित स्ट्रिंग पॉइंटर को मुक्त करता है। |
## संबंधित देखें

* नेमस्पेस [System::Runtime::InteropServices](../)
* लाइब्रेरी [Aspose.Slides](../../)