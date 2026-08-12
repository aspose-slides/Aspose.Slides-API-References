---
title: "System::StringExtra"
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 911
url: /hi/system.stringextra/
---
## फ़ंक्शन

| फ़ंक्शन | विवरण |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | स्ट्रिंग एरे को जोड़ता है। |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | स्ट्रिंग्स को जोड़ता है। |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | स्ट्रिंग्स को जोड़ता है। |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | स्ट्रिंग्स को जोड़ता है। |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | कई वस्तुओं को स्ट्रिंग में परिवर्तित करता है और प्राप्त स्ट्रिंग्स को जोड़ता है। विशेषीकृत [SmartPtr](../system/smartptr/) प्रकारों के लिए। |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | कई वस्तुओं को स्ट्रिंग में परिवर्तित करता है और प्राप्त स्ट्रिंग्स को जोड़ता है। विशेषीकृत अंकात्मक प्रकारों के लिए। |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | कई वस्तुओं को स्ट्रिंग में परिवर्तित करता है और प्राप्त स्ट्रिंग्स को जोड़ता है। विशेषीकृत संरचनाओं और अन्य मान प्रकारों के लिए। |