---
title: Round()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट मान को निकटतम पूर्णांक मान तक गोल करता है।
type: docs
weight: 157
url: /hi/system/math/round/
---
## Math::Round(double) मेथड

निर्दिष्ट मान को निकटतम पूर्णांक मान तक गोल करता है।

```cpp
static double System::Math::Round(double a)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| a | **double** | वह मान जिसे गोल करना है |

### रिटर्न मान

**a** को निकटतम पूर्णांक मान में गोल किया गया

## Math::Round(double, int) मेथड

निर्दिष्ट मान को निर्दिष्ट संख्या के दशमलव अंकों वाले निकटतम मान तक गोल करता है।

```cpp
static double System::Math::Round(double value, int digits)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | **double** | वह मान जिसे गोल करना है |
| digits | int | गोल किए गए मान में दशमलव अंकों की संख्या |

### रिटर्न मान

निर्दिष्ट अंकों की संख्या के साथ **value** के सबसे निकट का संख्या

## Math::Round(double, MidpointRounding) मेथड

निर्दिष्ट मान को निकटतम पूर्णांक संख्या तक गोल करता है। एक पैरामीटर निर्दिष्ट करता है कि यदि मान दो निकटतम संख्याओं के बराबर दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा।

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | **double** | वह मान जिसे गोल करना है |
| mode | [MidpointRounding](../../midpointrounding/) | यदि **value** दो निकटतम संख्याओं के बराबर दूरी पर हो तो गोल करने की विधि को निर्दिष्ट करता है। |

### रिटर्न मान

**value** को निकटतम पूर्णांक मान में गोल किया गया

## Math::Round(double, int, MidpointRounding) मेथड

निर्दिष्ट मान को निर्दिष्ट संख्या के दशमलव अंकों वाले निकटतम मान तक गोल करता है। एक पैरामीटर निर्दिष्ट करता है कि यदि मान दो निकटतम संख्याओं के बराबर दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा।

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | **double** | वह मान जिसे गोल करना है |
| digits | int | गोल किए गए मान में दशमलव अंकों की संख्या |
| mode | [MidpointRounding](../../midpointrounding/) | यदि **value** दो निकटतम संख्याओं के बराबर दूरी पर हो तो गोल करने की विधि को निर्दिष्ट करता है। |

### रिटर्न मान

निर्दिष्ट अंकों की संख्या के साथ **value** के सबसे निकट का संख्या

## Math::Round(const Decimal\&) मेथड

निर्दिष्ट मान को निकटतम पूर्णांक मान तक गोल करता है।

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | वह मान जिसे गोल करना है |

### रिटर्न मान

**d** को निकटतम पूर्णांक मान में गोल किया गया

## Math::Round(const Decimal\&, int) मेथड

निर्दिष्ट मान को निर्दिष्ट संख्या के दशमलव अंकों वाले निकटतम मान तक गोल करता है।

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | वह मान जिसे गोल करना है |
| digits | int | गोल किए गए मान में दशमलव अंकों की संख्या |

### रिटर्न मान

निर्दिष्ट अंकों की संख्या के साथ **value** के सबसे निकट का संख्या

## Math::Round(const Decimal\&, MidpointRounding) मेथड

निर्दिष्ट मान को निकटतम पूर्णांक संख्या तक गोल करता है। एक पैरामीटर निर्दिष्ट करता है कि यदि मान दो निकटतम संख्याओं के बराबर दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा।

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | वह मान जिसे गोल करना है |
| mode | [MidpointRounding](../../midpointrounding/) | यदि **value** दो निकटतम संख्याओं के बराबर दूरी पर हो तो गोल करने की विधि को निर्दिष्ट करता है। |

### रिटर्न मान

**d** को निकटतम पूर्णांक मान में गोल किया गया

## Math::Round(const Decimal\&, int, MidpointRounding) मेथड

निर्दिष्ट मान को निर्दिष्ट संख्या के दशमलव अंकों वाले निकटतम मान तक गोल करता है। एक पैरामीटर निर्दिष्ट करता है कि यदि मान दो निकटतम संख्याओं के बराबर दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा।

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | वह मान जिसे गोल करना है |
| digits | int | गोल किए गए मान में दशमलव अंकों की संख्या |
| mode | [MidpointRounding](../../midpointrounding/) | यदि **value** दो निकटतम संख्याओं के बराबर दूरी पर हो तो गोल करने की विधि को निर्दिष्ट करता है। |

### रिटर्न मान

निर्दिष्ट अंकों की संख्या के साथ **value** के सबसे निकट का संख्या

## संबंधित देखें

* Enum [MidpointRounding](../../midpointrounding/)
* क्लास [Decimal](../../decimal/)
* Struct [Math](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)