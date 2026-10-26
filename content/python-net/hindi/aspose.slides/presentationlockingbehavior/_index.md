---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior एन्यूमरेशन

[`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) स्रोत (फ़ाइल या **io.RawIOBase**) को लोड करने और [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) के एक उदाहरण के साथ काम करते समय कैसे संभालना है, इस व्यवहार का प्रतिनिधित्व करता है।

PresentationLockingBehavior प्रकार निम्नलिखित सदस्य प्रस्तुत करता है:

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| :- | :- |
| LOAD_AND_RELEASE | स्रोत को केवल [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) कंस्ट्रक्टर्स निष्पादन के समय के लिए ही लॉक किया जाएगा।<br/>यदि [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) को false सेट किया जाता है, तो सभी BLOBs <br/>मेमोरी में लोड हो जाएंगे। अन्यथा, अस्थायी फ़ाइलों जैसे अन्य उपाय उपयोग किए जा सकते हैं। यह व्यवहार [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/hi/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) की तुलना में धीमा है, और यदि स्रोत का अधिकार [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) को पास करना संभव हो, तो [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/hi/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) का उपयोग करने की सिफ़ारिश की जाती है। |
| KEEP_LOCKED | स्रोत को [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) इंस्टेंस के पूरे जीवनकाल के लिए लॉक किया जाएगा, जब तक कि इसे <br/>नष्ट नहीं किया जाता।<br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) को इस व्यवहार को उपयोग करने के लिए true पर सेट होना आवश्यक है, अन्यथा अपवाद फेंका जाएगा। यह व्यवहार सिफ़ारिश किया जाता है, यह [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/hi/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE) की तुलना में तेज़ है और कम मेमोरी उपभोग करता है। |

### टिप्पणियाँ

स्रोत वह पैरामीटर है जो [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) कंस्ट्रक्टर को पास किया जाता है। नीचे दिए गए उदाहरण में, स्रोत "pres.pptx" फ़ाइल है:

इस उदाहरण के लिए, स्रोत ("pres.pptx" फ़ाइल) [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) इंस्टेंस के जीवनकाल के लिए लॉक किया जाएगा, अर्थात इसे अन्य प्रक्रिया द्वारा बदला या हटाया नहीं जा सकेगा।

### देखें
* क्लास [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)