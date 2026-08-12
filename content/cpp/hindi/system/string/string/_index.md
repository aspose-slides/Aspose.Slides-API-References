---
title: String()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: डिफ़ॉल्ट कन्स्टरक्टर। एक स्ट्रिंग ऑब्जेक्ट बनाता है जिसे null माना जाता है।
type: docs
weight: 14
url: /hi/system/string/string/
---
## String::String() कन्स्ट्रक्टर


डिफ़ॉल्ट कन्स्ट्रक्टर। एक स्ट्रिंग ऑब्जेक्ट बनाता है जिसे null माना जाता है।

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) कन्स्ट्रक्टर


स्ट्रिंग लिटरल पर आधारित स्ट्रिंग बनाता है। लिटरल को null-समाप्त स्ट्रिंग माना जाता है, लिटरल के आकार के आधार पर लक्षित स्ट्रिंग की लंबाई गणना करता है।

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | T\& | [String](../) literal पॉइंटर। |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) कन्स्ट्रक्टर


कैरेक्टर स्ट्रिंग पॉइंटर पर आधारित स्ट्रिंग बनाता है। संकेतित स्ट्रिंग को null-समाप्त माना जाता है, null कैरेक्टर के आधार पर लक्षित स्ट्रिंग की लंबाई गणना करता है।

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const T\& | कैरेक्टर स्ट्रिंग पॉइंटर। |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) कन्स्ट्रक्टर


स्ट्रिंग लिटरल पर आधारित स्ट्रिंग बनाता है। लिटरल को UTF8 में null-समाप्त स्ट्रिंग माना जाता है, लिटरल के आकार के आधार पर लक्षित स्ट्रिंग की लंबाई गणना करता है।

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | T\& | [String](../) literal पॉइंटर। |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) कन्स्ट्रक्टर


कैरेक्टर स्ट्रिंग पॉइंटर पर आधारित स्ट्रिंग बनाता है। संकेतित स्ट्रिंग को UTF8 में null-समाप्त माना जाता है, null कैरेक्टर के आधार पर लक्षित स्ट्रिंग की लंबाई गणना करता है।

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const T\& | कैरेक्टर स्ट्रिंग पॉइंटर। |

## String::String(const char16_t *, int) कन्स्ट्रक्टर


कैरेक्टर स्ट्रिंग पॉइंटर और स्पष्ट लंबाई से स्ट्रिंग बनाता है।

```cpp
System::String::String(const char16_t *str, int length)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const char16_t * | [String](../) पॉइंटर, यह literal या array हो सकता है। |
| length | int | स्पष्ट स्ट्रिंग लंबाई |

## String::String(const ReadOnlySpan\<char16_t\>\&) कन्स्ट्रक्टर


निर्दिष्ट read-only स्पैन में दर्शाए गए Unicode अक्षरों के साथ [System.String](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Unicode अक्षरों का एक read-only स्पैन। |

## String::String(const char *, int) कन्स्ट्रक्टर


कैरेक्टर स्ट्रिंग पॉइंटर और स्पष्ट लंबाई से स्ट्रिंग बनाता है।

```cpp
System::String::String(const char *str, int length)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const char * | [String](../) पॉइंटर, UTF8 डेटा, यह literal या array हो सकता है। |
| length | int | स्पष्ट स्ट्रिंग लंबाई |

## String::String(const char16_t *, int, int) कन्स्ट्रक्टर


निर्दिष्ट प्रारंभिक स्थिति से लंबाई का उपयोग करके कैरेक्टर स्ट्रिंग पॉइंटर से स्ट्रिंग बनाता है।

```cpp
System::String::String(const char16_t *str, int start, int length)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const char16_t * | [String](../) पॉइंटर, यह literal या array हो सकता है। |
| start | int | प्रारंभिक स्थिति। |
| length | int | [String](../) लंबाई। |

## String::String(const char16_t, int) कन्स्ट्रक्टर


फ़िल कन्स्ट्रक्टर।

```cpp
System::String::String(const char16_t ch, int count)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| ch | const char16_t | फ़िल कैरेक्टर। |
| count | int | लक्षित लंबाई। |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) कन्स्ट्रक्टर


Nullptr कन्स्ट्रक्टर। अन्य टेम्पलेट कन्स्ट्रक्टरों के साथ प्राथमिकताएँ हल करने के लिए टेम्पलेट के रूप में घोषित किया गया है।

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | nullptr_t होना चाहिए |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) कन्स्ट्रक्टर


वाइड स्ट्रिंग लिटरल पर आधारित स्ट्रिंग बनाता है। लिटरल को null-समाप्त स्ट्रिंग माना जाता है, लिटरल के आकार के आधार पर लक्षित स्ट्रिंग की लंबाई गणना करता है। **wchar_t** से रूपांतरण कुछ प्लेटफ़ॉर्म पर समय-सापेक्ष है, इसलिए कोई निरपेक्ष रूपांतरण अनुमति नहीं है।

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | T\& | [String](../) literal पॉइंटर। |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) कन्स्ट्रक्टर


वाइड कैरेक्टर स्ट्रिंग पॉइंटर पर आधारित स्ट्रिंग बनाता है। संकेतित स्ट्रिंग को null-समाप्त माना जाता है, null कैरेक्टर के आधार पर लक्षित स्ट्रिंग की लंबाई गणना करता है। **wchar_t** से रूपांतरण कुछ प्लेटफ़ॉर्म पर समय-सापेक्ष है, इसलिए कोई निरपेक्ष रूपांतरण अनुमति नहीं है।

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const T\& | कैरेक्टर स्ट्रिंग पॉइंटर। |

## String::String(const wchar_t *, int) कन्स्ट्रक्टर


वाइड कैरेक्टर स्ट्रिंग पॉइंटर और स्पष्ट लंबाई से स्ट्रिंग बनाता है। **wchar_t** से रूपांतरण कुछ प्लेटफ़ॉर्म पर समय-सापेक्ष है, इसलिए कोई निरपेक्ष रूपांतरण अनुमति नहीं है।

```cpp
System::String::String(const wchar_t *str, int length)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) पॉइंटर, यह literal या array हो सकता है। |
| length | int | स्पष्ट स्ट्रिंग लंबाई |

## String::String(const wchar_t, int) कन्स्ट्रक्टर


फ़िल कन्स्ट्रक्टर। **wchar_t** से रूपांतरण कुछ प्लेटफ़ॉर्म पर समय-सापेक्ष है, इसलिए कोई निरपेक्ष रूपांतरण अनुमति नहीं है।

```cpp
System::String::String(const wchar_t ch, int count=1)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| ch | const **wchar_t** | फ़िल कैरेक्टर। |
| count | int | लक्षित लंबाई। |

## String::String(const String\&) कन्स्ट्रक्टर


कॉपी कन्स्ट्रक्टर।

```cpp
System::String::String(const String &str)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) कॉपी करने के लिए। |

## String::String(String\&&) कन्स्ट्रक्टर


मूव कन्स्ट्रक्टर।

```cpp
System::String::String(String &&str) noexcept
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) से डेटा मूव करने के लिए। |

## String::String(const ArrayPtr\<char16_t\>\&) कन्स्ट्रक्टर


पूरे कैरेक्टर एरे को स्ट्रिंग में परिवर्तित करता है।

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) को स्ट्रिंग में परिवर्तित करने के लिए। |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) कन्स्ट्रक्टर


कैरेक्टर एरे के उपनिर्धारित भाग को स्ट्रिंग में परिवर्तित करता है। यदि पैरामीटर एरे की सीमाओं से बाहर हैं, तो खाली स्ट्रिंग निर्मित होती है।

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | कैरेक्टर एरे। |
| offset | int | सबएरे प्रारंभिक इंडेक्स। |
| len | int | सबएरे लंबाई। |

## String::String(const codeporting_icu::UnicodeString\&) कन्स्ट्रक्टर


UnicodeString को [String](../) में रैप करता है।

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString को [String](../) में रैप करने के लिए। |

## String::String(codeporting_icu::UnicodeString\&&) कन्स्ट्रक्टर


मूव कन्स्ट्रक्टर।

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString को [String](../) में रैप करने के लिए। |

## String::String(const std::wstring\&) कन्स्ट्रक्टर


वाइडस्ट्रिंग से [String](../) बनाता है।

```cpp
System::String::String(const std::wstring &str)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const std::wstring\& | [String](../) में परिवर्तित करने के लिए वाइडस्ट्रिंग। |

## String::String(const std::u16string\&) कन्स्ट्रक्टर


utf16 स्ट्रिंग से [String](../) बनाता है।

```cpp
System::String::String(const std::u16string &str)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const std::u16string\& | [String](../) में परिवर्तित करने के लिए Utf16 स्ट्रिंग। |

## String::String(const std::string\&) कन्स्ट्रक्टर


UTF-8 प्रारूप में प्रस्तुत std::string स्ट्रिंग से [String](../) बनाता है।

```cpp
System::String::String(const std::string &utf8str)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| utf8str | const std::string\& | [String](../) में परिवर्तित करने के लिए std::string स्ट्रिंग। |

## String::String(const std::u32string\&) कन्स्ट्रक्टर


std::u32string स्ट्रिंग से [String](../) बनाता है।

```cpp
System::String::String(const std::u32string &u32str)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| u32str | const std::u32string\& | [String](../) में परिवर्तित करने के लिए std::u32string स्ट्रिंग। |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)