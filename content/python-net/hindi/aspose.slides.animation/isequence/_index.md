---
title: ISequence class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.animation/isequence/
---
## ISequence वर्ग

एक अनुक्रम (इफ़ेक्ट्स का संग्रह) को दर्शाता है।

ISequence प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## प्रॉपर्टी

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`count`](/slides/python-net/hi/aspose.slides.animation/isequence/count/) | एक अनुक्रम में इफ़ेक्ट्स की संख्या लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`trigger_shape`](/slides/python-net/hi/aspose.slides.animation/isequence/trigger_shape/) | INTERACTIVE अनुक्रम के लिए shape लक्ष्य को लौटाता है या सेट करता है।<br/>            यदि अनुक्रम इंटरैक्टिव नहीं है तो None लौटाता है।<br/>            पढ़ने/लिखने योग्य [`IShape`](/slides/python-net/hi/aspose.slides/ishape). |

निर्दिष्ट अनुक्रमांक पर एक इफ़ेक्ट लौटाता है।

## इंडेक्सर

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.animation/isequence/__getitem__/) | सूचकांक |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/hi/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | अनुक्रम के अंत में नया इफ़ेक्ट जोड़ता है। |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/hi/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | अनुक्रम के अंत में पैराग्राफ के लिए नया एनीमेशन इफ़ेक्ट जोड़ता है। |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/hi/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | अनुक्रम के अंत में श्रेणी या श्रृंखला के लिए नया चार्ट एनीमेशन इफ़ेक्ट जोड़ता है। |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/hi/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | अनुक्रम के अंत में श्रेणी या श्रृंखला के तत्वों के लिए नया चार्ट एनीमेशन इफ़ेक्ट जोड़ता है। |
| [`remove(self, item)`](/slides/python-net/hi/aspose.slides.animation/isequence/remove/#ieffect) | संकलन से निर्दिष्ट इफ़ेक्ट को हटाता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides.animation/isequence/remove_at/#int) | संकलन से एक इफ़ेक्ट हटाता है। |
| [`clear(self)`](/slides/python-net/hi/aspose.slides.animation/isequence/clear/#) | संकलन से सभी इफ़ेक्ट्स हटाता है। |
| [`remove_by_shape(self, shape)`](/slides/python-net/hi/aspose.slides.animation/isequence/remove_by_shape/#ishape) | निर्दिष्ट shape के लिए इफ़ेक्ट हटाता है। |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/hi/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | निर्दिष्ट shape के लिए इफ़ेक्ट्स का एरे लौटाता है। |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/hi/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | निर्दिष्ट पैराग्राफ के लिए इफ़ेक्ट्स का एरे लौटाता है। |
| [`get_count(self, shape)`](/slides/python-net/hi/aspose.slides.animation/isequence/get_count/#ishape) | निर्दिष्ट shape के लिए इफ़ेक्ट्स की गिनती लौटाता है। |

### देखें भी
* मॉड्यूल [`aspose.slides.animation`](/slides/python-net/hi/aspose.slides.animation)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)