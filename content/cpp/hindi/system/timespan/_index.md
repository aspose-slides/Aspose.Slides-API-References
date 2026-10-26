---
title: TimeSpan
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एक समय अंतराल का प्रतिनिधित्व करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या रेफ़रेंस द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 1314
url: /hi/system/timespan/
---
## TimeSpan क्लास

एक समय अंतराल का प्रतिनिधित्व करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन्स को मान या रेफ़रेंस द्वारा पास किया जाना चाहिए। इस प्रकार की ऑब्जेक्ट्स को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../smartptr/) क्लास का उपयोग न करें।

```cpp
class TimeSpan
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा प्रतिनिधित्व किए गए समय अंतरालों का योग दर्शाने वाला एक नया [TimeSpan](./) क्लास इंस्टेंस लौटाता है। |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | दो [TimeSpan](./) ऑब्जेक्ट्स की तुलना करता है। |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | वर्तमान और निर्दिष्ट ऑब्जेक्ट्स की तुलना करता है। |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | वर्तमान और निर्दिष्ट ऑब्जेक्ट्स की तुलना करता है। |
| [TimeSpan](./) [Duration](./duration/)() const | वर्तमान ऑब्जेक्ट के मान का निरपेक्ष मान दर्शाने वाला नया [TimeSpan](./) ऑब्जेक्ट इंस्टेंस लौटाता है। |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | जाँचता है कि क्या वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया समय अंतराल निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल के बराबर है। |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | जाँचता है कि क्या वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया समय अंतराल निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल के बराबर है। |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | यदि निर्दिष्ट ऑब्जेक्ट्स समान समय अंतराल का प्रतिनिधित्व करते हैं तो true लौटाता है, अन्यथा false। |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | निर्दिष्ट अंतराल का प्रतिनिधित्व करने वाला नया [TimeSpan](./) ऑब्जेक्ट लौटाता है। |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | निर्दिष्ट अंतराल का प्रतिनिधित्व करने वाला नया [TimeSpan](./) ऑब्जेक्ट लौटाता है। |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | निर्दिष्ट अंतराल का प्रतिनिधित्व करने वाला नया [TimeSpan](./) ऑब्जेक्ट लौटाता है। |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | निर्दिष्ट अंतराल का प्रतिनिधित्व करने वाला नया [TimeSpan](./) ऑब्जेक्ट लौटाता है। |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | निर्दिष्ट अंतराल का प्रतिनिधित्व करने वाला नया [TimeSpan](./) ऑब्जेक्ट लौटाता है। |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | निर्दिष्ट अंतराल का प्रतिनिधित्व करने वाला नया [TimeSpan](./) ऑब्जेक्ट लौटाता है। |
| constexpr int [get_Days](./get_days/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतकल का दिनों घटक लौटाता है। |
| constexpr int [get_Hours](./get_hours/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल का घंटों घटक लौटाता है। |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल का मिलीसेकंड घटक लौटाता है। |
| constexpr int [get_Minutes](./get_minutes/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल का मिनट घटक लौटाता है। |
| constexpr int [get_Seconds](./get_seconds/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल का सेकंड घटक लौटाता है। |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल को बनाने वाले 100-नैनोसेकंड अंतरालों की संख्या लौटाता है। |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट का मान पूर्ण और अंशीय दिनों में व्यक्त करके लौटाता है। |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट का मान पूर्ण और अंशीय घंटों में व्यक्त करके लौटाता है। |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट का मान पूर्ण और अंशीय मिलीसेकंड में व्यक्त करके लौटाता है। |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट का मान पूर्ण और अंशीय मिनट में व्यक्त करके लौटाता है। |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट का मान पूर्ण और अंशीय सेकंड में व्यक्त करके लौटाता है। |
| int [GetHashCode](./gethashcode/)() const | वर्तमान ऑब्जेक्ट के लिए एक हैश कोड लौटाता है। |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के नकारात्मक मान को दर्शाने वाला नया [TimeSpan](./) ऑब्जेक्ट इंस्टेंस लौटाता है। |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | जाँचता है कि क्या वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया समय अंतराल निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल के बराबर नहीं है। |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा प्रतिनिधित्व किए गए समय अंतरालों का योग दर्शाने वाला एक नया [TimeSpan](./) क्लास इंस्टेंस लौटाता है। |
| [TimeSpan](./) [operator+](./operator_plus/)() const | स्वयं लौटाता है। |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | वर्तमान ऑब्जेक्ट को वह समय अंतराल असाइन करता है जो वर्तमान और निर्दिष्ट ऑब्जेक्ट्स द्वारा प्रतिनिधित्व किए गए समय अंतरालों का योग है। |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल से निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल को घटाकर प्राप्त समय अंतराल को दर्शाने वाला नया [TimeSpan](./) क्लास इंस्टेंस लौटाता है। |
| [TimeSpan](./) [operator-](./operator_minus/)() const | वर्तमान [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के नकारात्मक मान को दर्शाने वाला नया [TimeSpan](./) ऑब्जेक्ट इंस्टेंस लौटाता है। |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | वर्तमान ऑब्जेक्ट को वह समय अंतराल असाइन करता है जो वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल से निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल को घटाने का परिणाम है। |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | जाँचता है कि क्या वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया समय अंतराल निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल से छोटा है। |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | जाँचता है कि क्या वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया समय अंतराल निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल से छोटा या बराबर है। |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | निर्दिष्ट [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल को वर्तमान [TimeSpan](./) ऑब्जेक्ट में सेट करता है। |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | जाँचता है कि क्या वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया समय अंतराल निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल के बराबर है। |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | जाँचता है कि क्या वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया समय अंतराल निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल से लंबा है। |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | जाँचता है कि क्या वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया समय अंतराल निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल से लंबा या बराबर है। |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है। |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट फ़ॉर्मेट प्रोवाइडर का उपयोग करके स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है। |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | निर्दिष्ट फ़ॉर्मैट, फ़ॉर्मेट प्रोवाइडर और स्टाइल्स का उपयोग करके स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है। |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | निर्दिष्ट फ़ॉर्मेट, फ़ॉर्मेट प्रोवाइडर और स्टाइल्स का उपयोग करके स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है। |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल से निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल को घटाकर प्राप्त समय अंतराल को दर्शाने वाला नया [TimeSpan](./) क्लास इंस्टेंस लौटाता है। |
| constexpr [TimeSpan](./timespan/)() | एक शून्य समय अंतराल का प्रतिनिधित्व करने वाला [TimeSpan](./) ऑब्जेक्ट बनाता है। |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | निर्दिष्ट समय अंतराल का प्रतिनिधित्व करने वाला [TimeSpan](./) क्लास का एक इंस्टेंस बनाता है। |
| [TimeSpan](./timespan/)(int, int, int) | निर्दिष्ट घंटों, मिनटों और सेकंडों की संख्या का योग दर्शाने वाला समय अंतराल प्रतिनिधित्व करने वाला [TimeSpan](./) क्लास का एक इंस्टेंस बनाता है। |
| [TimeSpan](./timespan/)(int, int, int, int, int) | निर्दिष्ट घंटों, मिनटों, सेकंडों और मिलीसेकंडों की संख्या का योग दर्शाने वाला समय अंतराल प्रतिनिधित्व करने वाला [TimeSpan](./) क्लास का एक इंस्टेंस बनाता है। |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | निर्दिष्ट [TimeSpan](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल के बराबर समय अंतराल का प्रतिनिधित्व करने वाला [TimeSpan](./) ऑब्जेक्ट बनाता है। |
| [String](../string/) [ToString](./tostring/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए समय अंतराल का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | निर्दिष्ट फ़ॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट के मान को समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | निर्दिष्ट फ़ॉर्मेट और फ़ॉर्मेट प्रोवाइडर का उपयोग करके वर्तमान ऑब्जेक्ट के मान को समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है और रूपांतरण का परिणाम लौटाता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | निर्दिष्ट फ़ॉर्मेट प्रोवाइडर का उपयोग करके स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है और रूपांतरण का परिणाम लौटाता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | निर्दिष्ट फ़ॉर्मेट और फ़ॉर्मेट प्रोवाइडर का उपयोग करके स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है और रूपांतरण का परिणाम लौटाता है। |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | निर्दिष्ट फ़ॉर्मेट, फ़ॉर्मेट प्रोवाइडर और स्टाइल्स का उपयोग करके स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है और रूपांतरण का परिणाम लौटाता है। |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | निर्दिष्ट फ़ॉर्मेट, फ़ॉर्मेट प्रोवाइडर और स्टाइल्स का उपयोग करके स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है और रूपांतरण का परिणाम लौटाता है। |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | निर्दिष्ट फ़ॉर्मेट और फ़ॉर्मेट प्रोवाइडर का उपयोग करके स्ट्रिंग को समतुल्य [TimeSpan](./) ऑब्जेक्ट में परिवर्तित करता है और रूपांतरण का परिणाम लौटाता है। |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | एक [TypeInfo](../typeinfo/) ऑब्जेक्ट लौटाता है जो [TimeSpan](./) संरचना का प्रतिनिधित्व करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [MaxValue](./maxvalue/) | सबसे लंबा संभव अंतराल दर्शाने वाला [TimeSpan](./) ऑब्जेक्ट। |
| static [MinValue](./minvalue/) | /// सबसे छोटा संभव अंतराल दर्शाने वाला [TimeSpan](./) ऑब्जेक्ट। |
| static constexpr [TicksPerDay](./ticksperday/) | एक दिन (24-घंटे का अंतराल) में 100-नैनोसेकंड अंतरालों की संख्या। |
| static constexpr [TicksPerHour](./ticksperhour/) | एक घंटे में 100-नैनोसेकंड अंतरालों की संख्या। |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | एक मिलीसेकंड में 100-नैनोसेकंड अंतरालों की संख्या। |
| static constexpr [TicksPerMinute](./ticksperminute/) | एक मिनट में 100-नैनोसेकंड अंतरालों की संख्या। |
| static constexpr [TicksPerSecond](./tickspersecond/) | एक सेकंड में 100-नैनोसेकंड अंतरालों की संख्या। |
| static [Zero](./zero/) | शून्य-अंतराल दर्शाने वाला [TimeSpan](./) ऑब्जेक्ट। |

## टिप्पणी

```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
टिक्स की संख्या: 260928000000000
मिलिसेकंड की संख्या: 0
कुल मिलिसेकंड की संख्या: 2.60928e+10
मिनटों की संख्या: 0
कुल मिनटों की संख्या: 434880
घंटों की संख्या: 0
कुल घंटों की संख्या: 0
दिनों की संख्या: 302
कुल दिनों की संख्या: 302
*/
```

## अन्य देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)