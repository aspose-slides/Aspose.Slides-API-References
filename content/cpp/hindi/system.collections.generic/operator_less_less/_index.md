---
title: operator<<()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: UTF-8 एन्कोडिंग का उपयोग करके स्ट्रीम में डेटा डालें।
type: docs
weight: 716
url: /hi/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream&, const KeyValuePair<TKey, TValue>&) फ़ंक्शन


UTF-8 एन्कोडिंग का उपयोग करके स्ट्रीम में डेटा डालें।

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कुंजी प्रकार। |
| TValue | मान प्रकार। |

### पैरामीटर

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | std::ostream& | डेटा डालने के लिए आउटपुट स्ट्रीम। |
| pair | const [KeyValuePair](../keyvaluepair/)<TKey, TValue>& | [Data](../../system.data/) डालने के लिए। |

### वापसी मान

**stream**.

## System::Collections::Generic::operator<<(std::wostream&, const KeyValuePair<TKey, TValue>&) फ़ंक्शन


स्ट्रीम में डेटा डालें।

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कुंजी प्रकार। |
| TValue | मान प्रकार। |

### पैरामीटर

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | std::wostream& | डेटा डालने के लिए आउटपुट स्ट्रीम। |
| pair | const [KeyValuePair](../keyvaluepair/)<TKey, TValue>& | [Data](../../system.data/) डालने के लिए। |

### वापसी मान

**stream**.

## संबंधित देखें

* क्लास [KeyValuePair](../keyvaluepair/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)