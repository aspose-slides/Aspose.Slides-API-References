---
title: Parse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समान एकल-प्रेसिशन फ़्लोटिंग-पॉइंट मान में परिवर्तित करता है।
type: docs
weight: 1
url: /hi/system/single/parse/
---
## Single::Parse(const String\&) विधि

निर्दिष्ट स्ट्रिंग जिसे संख्या की स्ट्रिंग प्रतिनिधित्व के रूप में दर्शाया गया है, को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है।

```cpp
static float System::Single::Parse(const String &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |

### रिटर्न मान

निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान।

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) विधि

प्रदान किए गए फॉर्मेटिंग जानकारी का उपयोग करके, निर्दिष्ट स्ट्रिंग जिसे संख्या की स्ट्रिंग प्रतिनिधित्व के रूप में दर्शाया गया है, को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है।

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक पॉइंटर जो उस ऑब्जेक्ट की ओर इशारा करता है जिसमें स्ट्रिंग फ़ॉर्मेट सूचना होती है। |

### रिटर्न मान

निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान।

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) विधि




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) विधि




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) विधि

प्रदान किए गए फॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके, निर्दिष्ट स्ट्रिंग जिसे संख्या की स्ट्रिंग प्रतिनिधित्व के रूप में दर्शाया गया है, को समान एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है।

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles ए़नम के मानों का बिटवाइज़ संयोजन जो संख्या की स्ट्रिंग प्रतिनिधित्व के अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक पॉइंटर जो उस ऑब्जेक्ट की ओर इशारा करता है जिसमें स्ट्रिंग फ़ॉर्मेट सूचना होती है। |

### रिटर्न मान

निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर एकल-प्रेसिशन फ्लोटिंग-पॉइंट मान।

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) विधि




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) विधि




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## देखें भी

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)