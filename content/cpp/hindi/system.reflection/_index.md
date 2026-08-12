---
title: "System::Reflection"
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 755
url: /hi/system.reflection/
---
## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) क्लास जो assembly का वर्णन करता है। समर्थन सीमित है क्योंकि नियम C# और C++ के बीच काफी अलग हैं। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन्स में आर्ग्युमेंट के रूप में पास करने के लिए करें। |
| [AssemblyName](./assemblyname/) | assembly नाम परिभाषित करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन्स में आर्ग्युमेंट के रूप में पास करने के लिए करें। |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | चल रही assembly में प्रकार को पंजीकृत करने के लिए सिंगलटन। |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | चल रही assembly में प्रकार को पंजीकृत करने वाले सिंगलटन्स के लिए बेस टाइप। |
| [ConstructorInfo](./constructorinfo/) | कन्स्ट्रक्टर मेटाडेटा तक पहुँच प्रदान करता है। |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException को Module.GetTypes मेथड द्वारा थ्रॉ किया जाता है यदि किसी मॉड्यूल की किसी क्लास को लोड करने में विफलता होती है। इस क्लास के इंस्टेंस को मैन्युअल रूप से कभी बनाएं नहीं। इसके बजाय ReflectionTypeLoadException क्लास का उपयोग करें। ReflectionTypeLoadException क्लास के इंस्टेंस को कभी भी [System::SmartPtr](../system/smartptr/) में लपेटें नहीं। |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException को रिफ्लेक्शन के माध्यम से इनवोक किए गए मेथड्स द्वारा थ्रॉ किया जाता है। इस क्लास के इंस्टेंस को मैन्युअल रूप से कभी बनाएं नहीं। इसके बजाय TargetInvocationException क्लास का उपयोग करें। TargetInvocationException क्लास के इंस्टेंस को कभी भी [System::SmartPtr](../system/smartptr/) में लपेटें नहीं। |
| [FieldInfo](./fieldinfo/) | फ़ील्ड के एट्रिब्यूट्स को खोजता है और फ़ील्ड मेटाडेटा तक पहुँच प्रदान करता है। |
| [MemberInfo](./memberinfo/) | सदस्यों पर रिफ्लेक्शन जानकारी प्रदान करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन्स में आर्ग्युमेंट के रूप में पास करने के लिए करें। |
| [MethodBase](./methodbase/) | मेथड पर बेस जानकारी। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन्स में आर्ग्युमेंट के रूप में पास करने के लिए करें। |
| [MethodInfo](./methodinfo/) | क्लास मेथड पर जानकारी का प्रतिनिधित्व करता है। |
| [PropertyInfo](./propertyinfo/) | प्रॉपर्टी जानकारी का प्रतिनिधित्व करता है। |
## एनम्स

| एनम | विवरण |
| --- | --- |
| [BindingFlags](./bindingflags/) | सदस्यों और टाइप लुकअप मोड्स तथा बाइंडिंग्स को परिभाषित करता है। |
| [FieldAttributes](./fieldattributes/) | रिफ्लेक्टेड फ़ील्ड एट्रिब्यूट्स। |
| [MemberTypes](./membertypes/) | प्रत्येक सदस्य प्रकार को चिन्हित करता है। |
## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException को Module.GetTypes मेथड द्वारा थ्रॉ किया जाता है यदि मॉड्यूल की किसी क्लास को लोड करने में विफलता होती है। ReflectionTypeLoadException क्लास के इंस्टेंस को कभी भी [System::SmartPtr](../system/smartptr/) में लपेटें नहीं। |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException को रिफ्लेक्शन के माध्यम से इनवोक किए गए मेथड्स द्वारा थ्रॉ किया जाता है। TargetInvocationException क्लास के इंस्टेंस को कभी भी [System::SmartPtr](../system/smartptr/) में लपेटें नहीं। |