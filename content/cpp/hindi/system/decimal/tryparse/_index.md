---
title: TryParse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, उसे समकक्ष Decimal मान में परिवर्तित करता है।
type: docs
weight: 482
url: /hi/system/decimal/tryparse/
---
## Decimal::TryParse(const String&, Decimal&) विधि

निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, उसे समतुल्य [Decimal](../) मान में परिवर्तित करता है।

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग |
| result | [Decimal](../)\& | परिवर्तन के परिणाम को रखने वाले [Decimal](../) वेरिएबल का रेफ़रेंस |

### रिटर्न वैल्यू

यदि परिवर्तन सफल हो तो True, अन्यथा - false

## Decimal::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal&) विधि

निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, प्रदान की गई फ़ॉर्मेटिंग जानकारी और नंबर शैली का उपयोग करके समतुल्य [Decimal](../) मान में परिवर्तित करता है।

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली को निर्दिष्ट करता है |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जिसमें स्ट्रिंग फॉर्मेट जानकारी होती है |
| result | [Decimal](../)\& | एक आउटपुट आर्ग्युमेंट; परिवर्तन का परिणाम रखता है |

### रिटर्न वैल्यू

यदि परिवर्तन सफल हो तो True, अन्यथा - false

## संबंधित देखें

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)