---
title: Debug
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डिबग मेथड्स का संग्रह जो पंजीकृत लिस्नर्स को डिबग जानकारी भेजने की अनुमति देता है। सभी आउटपुट फ़ंक्शन केवल Debug में काम करते हैं। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इसे किसी भी माध्यम से इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 105
url: /hi/system.diagnostics/debug/
---
## डिबग संरचना

डिबग मेथड्स का संग्रह जो पंजीकृत लिस्नर्स को डिबग जानकारी भेजने की अनुमति देता है। सभी आउटपुट फ़ंक्शन केवल [Debug](./) में काम करते हैं। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इसे किसी भी माध्यम से इंस्टेंस नहीं बनाना चाहिए।

```cpp
class Debug
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | शर्त की पुष्टि करें और विफलता पर जानकारी भेजें। |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | शर्त की पुष्टि करें और विफलता पर जानकारी भेजें। |
| static void [Assert](./assert/)(**bool**, const char *) | शर्त की पुष्टि करें और विफलता पर जानकारी भेजें। |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | शर्त की पुष्टि करें और विफलता पर जानकारी भेजें। |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | विफल संदेश भेजें। |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | लिस्नर्स की स्थैतिक सूची तक पहुँचता है। |
| static void [Print](./print/)(const [String](../../system/string/)\&) | संदेश को डिबग इंटरफ़ेस पर प्रिंट करता है। |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | संदेश को डिबग इंटरफ़ेस पर प्रिंट करता है। |
| static void [Write](./write/)(const [String](../../system/string/)\&) | स्ट्रिंग को डिबग इंटरफ़ेस पर लिखता है। |
| static void [Write](./write/)(const char_t *) | स्ट्रिंग को डिबग इंटरफ़ेस पर लिखता है। |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | यदि शर्त सत्य है तो डिबग इंटरफ़ेस पर स्ट्रिंग लिखता है। |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | लाइन को डिबग इंटरफ़ेस पर लिखता है। |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | लाइन को डिबग इंटरफ़ेस पर लिखता है। |
| static void [WriteLine](./writeline/)(const char_t *) | लाइन को डिबग इंटरफ़ेस पर लिखता है। |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | लाइन को डिबग इंटरफ़ेस पर लिखता है। |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | यदि शर्त सत्य है तो डिबग इंटरफ़ेस पर लाइन लिखता है। |

## देखें भी

* नामस्थान [System::Diagnostics](../)
* लाइब्रेरी [Aspose.Slides](../../)