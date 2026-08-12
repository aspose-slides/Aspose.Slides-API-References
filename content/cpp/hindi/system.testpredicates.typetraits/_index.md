---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: 
type: docs
weight: 963
url: /hi/system.testpredicates.typetraits/
---
## संरचनाएँ

| Struct | Description |
| --- | --- |
| [has_data_method](./has_data_method/) | जांचता है कि क्या किसी प्रकार में data() मेथड है। यदि है, तो std::true_type को विरासत में लेता है, अन्यथा std::false_type को विरासत में लेता है। |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | BitArray प्रकार के लिए विशेषीकरण जो boost प्रकार प्रदान करता है जो वहाँ पहुँच योग्य नहीं है। |
| [has_print_to_method](./has_print_to_method/) | जांचता है कि PrintTo फ़ंक्शन का कोई ओवरलोड उपलब्ध है जो दिए गए प्रकार को प्रथम तर्क के रूप में स्वीकार करता है। यदि ओवरलोड मौजूद है, तो std::true_type को विरासत में लेता है, अन्यथा std::false_type को विरासत में लेता है। |
| [IsCppContainer](./iscppcontainer/) | जांचता है कि क्या विशिष्ट प्रकार STL-शीैली का कंटेनर है। इसके लिए iterator और const_iterator सदस्य प्रकारों की उपस्थिति जाँची जाती है। यदि दोनों मौजूद हैं, तो std::true_type को विरासत में लेता है, अन्यथा std::false_type को विरासत में लेता है। |
| [IsEnumerable](./isenumerable/) | जाँचता है कि प्रकार के पास [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) विशेषीकरण बेस-टाइप के रूप में है। यदि हाँ, तो value सदस्य को true सेट किया जाता है, अन्यथा इसे false सेट किया जाता है। |
| [LargestFPType](./largestfptype/) | प्रदान किए गए सबसे लंबे फ्लोटिंग-पॉइंट प्रकार के लिए उपनाम प्रदान करता है। गैर-फ्लोटिंग-पॉइंट प्रकारों को अनदेखा करता है। |

## टाइपडिफ़्स

| Typedef | Description |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | जांचता है कि **T1** अंकगणितीय है और **T2** फ्लोटिंग-पॉइंट है, या इसके विपरीत। यदि हाँ, तो value सदस्य को true सेट करता है, अन्यथा इसे false सेट करता है। |
| [AnyOfDecimal](./anyofdecimal/) | जांचता है कि प्रकार तर्कों में से कम से कम एक [System::Decimal](../system/decimal/) है। यदि हाँ, तो value सदस्य को true सेट करता है, अन्यथा इसे false सेट करता है। |
| [IsArray](./isarray/) | जाँचता है कि प्रकार [System::Array](../system/array/) विशेषीकरण है। यदि हाँ, तो value सदस्य को true सेट किया जाता है, अन्यथा इसे false सेट किया जाता है। |
| [IsList](./islist/) | जाँचता है कि प्रकार [System::Collections::Generic::List](../system.collections.generic/list/) विशेषीकरण है। यदि हाँ, तो value सदस्य को true सेट किया जाता है, अन्यथा इसे false सेट किया जाता है। |
| [BothArrayOrList](./botharrayorlist/) | जाँचता है कि दोनों प्रकार तर्क एरेज़ या सूचियाँ हैं। यदि हाँ, तो value सदस्य को true सेट किया जाता है, अन्यथा इसे false सेट किया जाता है। |
| [BothEnumerable](./bothenumerable/) | जाँचता है कि दोनों प्रकार तर्क IEnumerable हैं। यदि हाँ, तो value सदस्य को true सेट किया जाता है, अन्यथा इसे false सेट किया जाता है। |