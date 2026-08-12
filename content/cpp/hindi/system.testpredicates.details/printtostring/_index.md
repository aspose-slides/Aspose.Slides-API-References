---
title: PrintToString()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: उचित सीरियलाइज़र फ़ंक्शन का चयन करके वस्तु को स्ट्रिंग में प्रिंट करता है।
type: docs
weight: 1
url: /hi/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) फ़ंक्शन

ऑब्जेक्ट को स्ट्रिंग में प्रिंट करता है उचित सीरियलाइज़र फ़ंक्शन का चयन करके।

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) को प्रिंट करने के लिए। |

### रिटर्न वैल्यू

[String](../../system/string/) पास किए गए ऑब्जेक्ट के प्रतिनिधित्व।

## System::TestPredicates::Details::PrintToString(const T\&) फ़ंक्शन

ICollection-स्टाइल कंटेनरों को स्ट्रिंग में प्रिंट करता है उनके तत्वों को प्रिंट करके (अधिकतम 32)।

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) को प्रिंट करने के लिए। |

### रिटर्न वैल्यू

शामिल तत्वों के संयुक्त स्ट्रिंग प्रतिनिधित्व।

## System::TestPredicates::Details::PrintToString(std::nullptr_t) फ़ंक्शन

nullptr को स्ट्रिंग में प्रिंट करता है।

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### रिटर्न वैल्यू

"nullptr" स्ट्रिंग।

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) फ़ंक्शन

[IEnumerable<bool>](../../system.collections.generic/ienumerable/) संग्रहों को स्ट्रिंग में प्रिंट करता है उनके तत्वों को प्रिंट करके (अधिकतम 32)।

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) को प्रिंट करने के लिए। |

### रिटर्न वैल्यू

शामिल तत्वों के संयुक्त स्ट्रिंग प्रतिनिधित्व।

## देखें भी

* वर्ग [IEnumerable](../../system.collections.generic/ienumerable/)
* संरचना [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* नामस्थान [System::TestPredicates::Details](../)
* पुस्तकालय [Aspose.Slides](../../)