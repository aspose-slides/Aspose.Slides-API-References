---
title: GetDateTimeFormats()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व, प्रत्येक तत्व में, मानक तिथि और समय फ़ॉर्मेट स्पेसिफायर में से एक के साथ फ़ॉर्मेट किया हुआ, वाली स्ट्रिंग्स की एरे लौटाता है।
type: docs
weight: 547
url: /hi/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const विधि

वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व, प्रत्येक तत्व में, मानक तिथि और समय फ़ॉर्मेट स्पेसिफायर में से एक के साथ फ़ॉर्मेट किया हुआ, वाली स्ट्रिंग्स की एरे लौटाता है।

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const विधि

वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व, प्रत्येक तत्व में, निर्दिष्ट मानक तिथि और समय फ़ॉर्मेट स्पेसिफायर के साथ फ़ॉर्मेट किया हुआ, वाली स्ट्रिंग्स की एरे लौटाता है।

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | char_t | मानक तिथि और समय फ़ॉर्मेट स्पेसिफायर। |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const विधि

वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व, प्रत्येक तत्व में, मानक तिथि और समय फ़ॉर्मेट स्पेसिफायर में से एक और निर्दिष्ट फ़ॉर्मेट प्रोवाइडर के साथ फ़ॉर्मेट किया हुआ, वाली स्ट्रिंग्स की एरे लौटाता है।

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर। |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const विधि

वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व, प्रत्येक तत्व में, निर्दिष्ट मानक तिथि और समय फ़ॉर्मेट स्पेसिफायर और फ़ॉर्मेट प्रोवाइडर के साथ फ़ॉर्मेट किया हुआ, वाली स्ट्रिंग्स की एरे लौटाता है।

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | char_t | मानक तिथि और समय फ़ॉर्मेट स्पेसिफायर। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रोवाइडर। |

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)