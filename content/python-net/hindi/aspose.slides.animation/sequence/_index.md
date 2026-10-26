---
title: Sequence class
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.animation/sequence/
---
## Sequence क्लास

सीक्वेंस (इफ़ेक्ट्स का संग्रह) का प्रतिनिधित्व करता है।

Sequence प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## प्रॉपर्टी

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`count`](/slides/python-net/hi/aspose.slides.animation/sequence/count/) | सीक्वेंस में प्रभावों की संख्या लौटाता है।<br/>            केवल-पढ़ने-योग्य **int**. |
| [`trigger_shape`](/slides/python-net/hi/aspose.slides.animation/sequence/trigger_shape/) | INTERACTIVE सीक्वेंस के लिए shape लक्ष्य को प्राप्त करता है या सेट करता है।<br/>            यदि सीक्वेंस इंटरैक्टिव नहीं है तो None लौटाता है।<br/>            पढ़ें/लिखें [`IShape`](/slides/python-net/hi/aspose.slides/ishape). |

निर्दिष्ट अनुक्रमांक पर एक इफ़ेक्ट लौटाता है।

## इंडेक्सर

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.animation/sequence/__getitem__/) |  |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/hi/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | नई इफ़ेक्ट को सीक्वेंस के अंत में जोड़ता है। |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/hi/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | पैराग्राफ के लिए नई एनीमेशन इफ़ेक्ट को सीक्वेंस के अंत में जोड़ता है। |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/hi/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | श्रेणी या श्रृंखला के लिए नई चार्ट एनीमेशन इफ़ेक्ट को सीक्वेंस के अंत में जोड़ता है। |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/hi/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | श्रेणी या श्रृंखला के तत्वों के लिए नई चार्ट एनीमेशन इफ़ेक्ट को सीक्वेंस के अंत में जोड़ता है। |
| [`remove(self, item)`](/slides/python-net/hi/aspose.slides.animation/sequence/remove/#ieffect) | संग्रह से निर्दिष्ट इफ़ेक्ट को हटाता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides.animation/sequence/remove_at/#int) | संग्रह से एक इफ़ेक्ट को हटाता है। |
| [`clear(self)`](/slides/python-net/hi/aspose.slides.animation/sequence/clear/#) | संग्रह से सभी इफ़ेक्ट्स को हटाता है। |
| [`remove_by_shape(self, shape)`](/slides/python-net/hi/aspose.slides.animation/sequence/remove_by_shape/#ishape) | निर्दिष्ट shape के लिए इफ़ेक्ट को हटाता है। |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/hi/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | निर्दिष्ट shape के लिए इफ़ेक्ट्स का array लौटाता है। |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/hi/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | निर्दिष्ट पैराग्राफ के लिए इफ़ेक्ट्स का array लौटाता है। |
| [`get_count(self, shape)`](/slides/python-net/hi/aspose.slides.animation/sequence/get_count/#ishape) | निर्दिष्ट shape के लिए इफ़ेक्ट्स की गणना लौटाता है। |

### देखें
* मॉड्यूल [`aspose.slides.animation`](/slides/python-net/hi/aspose.slides.animation)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)