---
title: WriteAllLines()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट एन्कोडिंग का उपयोग करते हुए, निर्दिष्ट एन्यूमेरेबल स्ट्रिंग संग्रह से सभी स्ट्रिंग्स को नई पंक्तियों में लिखकर, नया टेक्स्ट फ़ाइल बनाता है या मौजूदा फ़ाइल को अधिलेखित करता है।
type: docs
weight: 456
url: /hi/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method

निर्दिष्ट एन्कोडिंग का उपयोग करते हुए, निर्दिष्ट एन्यूमेरेबल स्ट्रिंग संग्रह से सभी स्ट्रिंग्स को नई पंक्तियों में लिखकर, नया टेक्स्ट फ़ाइल बनाता है या मौजूदा फ़ाइल को अधिलेखित करता है।

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | बनाने या अधिलेखित करने के लिये फ़ाइल |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | स्ट्रिंग्स का एन्यूमेरेबल संग्रह |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिये अक्षर एन्कोडिंग |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) method

निर्दिष्ट एन्कोडिंग का उपयोग करते हुए, निर्दिष्ट स्ट्रिंग एरे से सभी स्ट्रिंग्स को नई पंक्तियों में लिखकर, नया टेक्स्ट फ़ाइल बनाता है या मौजूदा फ़ाइल को अधिलेखित करता है।

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | बनाने या अधिलेखित करने के लिये फ़ाइल |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | स्ट्रिंग एरे |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिये अक्षर एन्कोडिंग |

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)