---
title: LastIndexOfAny()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: पूरा स्ट्रिंग पीछे की ओर खोजते हुए पास किए गए किसी भी अक्षर को ढूँढ़ता है। अंतिम स्ट्रिंग अक्षर की तुलना anyOf में सभी अक्षरों से करता है, फिर पिछले अक्षर की तुलना करता है और इस प्रकार आगे बढ़ता है। पहला मिलान मिलने पर उसका इंडेक्स लौटाता है।
type: docs
weight: 664
url: /hi/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const विधि

पूरा स्ट्रिंग पीछे की ओर खोजते हुए पास किए गए किसी भी अक्षर को ढूँढ़ता है। अंतिम स्ट्रिंग अक्षर की तुलना anyOf में सभी अक्षरों से करता है, फिर पिछले अक्षर की और इस प्रकार आगे बढ़ता है। पहला मिलान मिलने पर उसका इंडेक्स लौटाता है।

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) खोजे जाने वाले अक्षरों में से। क्रम का महत्व नहीं है। |

### वापसी मान

[Index](../../index/) अंतिम मिलान करने वाले अक्षर का इंडेक्स, या यदि नहीं मिला तो -1।

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const विधि

उपस्ट्रिंग पीछे की ओर खोजते हुए पास किए गए किसी भी अक्षर को ढूँढ़ता है। अंतिम स्ट्रिंग अक्षर की तुलना anyOf में सभी अक्षरों से करता है, फिर पिछले अक्षर की और इस प्रकार आगे बढ़ता है। पहला मिलान मिलने पर उसका इंडेक्स लौटाता है।

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) खोजे जाने वाले अक्षरों में से। क्रम का महत्व नहीं है। |
| startindex | **int32_t** | [Index](../../index/) से खोज शुरू करने के लिए। |

### वापसी मान

[Index](../../index/) अंतिम मिलान करने वाले अक्षर का इंडेक्स, या यदि नहीं मिला तो -1।

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const विधि

उपस्ट्रिंग पीछे की ओर खोजते हुए पास किए गए किसी भी अक्षर को ढूँढ़ता है। अंतिम स्ट्रिंग अक्षर की तुलना anyOf में सभी अक्षरों से करता है, फिर पिछले अक्षर की और इस प्रकार आगे बढ़ता है। पहला मिलान मिलने पर उसका इंडेक्स लौटाता है।

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) खोजे जाने वाले अक्षरों में से। क्रम का महत्व नहीं है। |
| startindex | **int32_t** | [Index](../../index/) से खोज शुरू करने के लिए। |
| count | **int32_t** | देखे जाने वाले अक्षरों की संख्या। |

### वापसी मान

[Index](../../index/) अंतिम मिलान करने वाले अक्षर का इंडेक्स, या यदि नहीं मिला तो -1।

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)