---
title: Range
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक रेंज का प्रतिनिधित्व करता है जिसमें प्रारंभ और समाप्ति इंडेक्स होता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों में मान द्वारा या संदर्भ द्वारा पास किया जाना चाहिए। कभी भी System::SmartPtr वर्ग का उपयोग इस प्रकार की वस्तुओं को प्रबंधित करने के लिए न करें।"
type: docs
weight: 1197
url: /hi/system/range/
---
## Range वर्ग

एक रेंज को दर्शाता है जिसमें प्रारंभ और समाप्ति अंकांक होते हैं। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों में मान द्वारा या संदर्भ द्वारा पास किया जाना चाहिए। कभी भी [System::SmartPtr](../smartptr/) वर्ग का उपयोग इस प्रकार की वस्तुओं को प्रबंधित करने के लिए न करें।

```cpp
class Range : public System::Details::BoxableObjectBase
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | एक रेंज बनाता है जो संग्रह की शुरुआत से शुरू होती है और निर्दिष्ट समाप्ति अंकांक पर समाप्त होती है। |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | निर्धारित करता है कि वर्तमान रेंज निर्दिष्ट रेंज के बराबर है या नहीं। |
| static constexpr [Range](./) [get_All](./get_all/)() | एक [Range](./) लौटाता है जो सम्पूर्ण संग्रह का प्रतिनिधित्व करता है। |
| const [Index](../index/)\& [get_End](./get_end/)() const | End इंडेक्स प्राप्त करता है। |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Start इंडेक्स प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const | वर्तमान रेंज के लिए हैश कोड लौटाता है। |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | निर्दिष्ट संग्रह लंबाई के लिए शून्य-आधारित प्रारम्भ ऑफसेट और लंबाई की गणना करता है। |
| constexpr [Range](./range/)() | एक खाली रेंज बनाता है। |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | निर्दिष्ट प्रारम्भ और समाप्ति अंकांकों से एक [Range](./) बनाता है। |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | एक रेंज बनाता है जो निर्दिष्ट प्रारम्भ अंकांक से शुरू होती है और संग्रह के अंत तक विस्तारित होती है। |

## देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)