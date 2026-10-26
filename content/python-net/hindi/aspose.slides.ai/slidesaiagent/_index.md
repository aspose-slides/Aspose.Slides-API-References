---
title: SlidesAIAgent class
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent क्लास

प्रेजेंटेशन को प्रोसेस करने के लिए AI-संचालित सुविधाएँ प्रदान करता है।

SlidesAIAgent प्रकार निम्नलिखित सदस्यों को प्रदर्शित करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | [`SlidesAIAgent`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent) का नया उदाहरण कस्टम AI क्लाइंट के साथ आरंभ करता है।<br/>AI प्रदाता निर्दिष्ट करने, अपना स्वयं का LLM प्रदान करने, या इसे कस्टमाइज़ करने के लिए इस ओवरलोड का उपयोग करें।<br/>कनेक्शन (उदाहरण के लिए, अपना खुद का `HttpClient` प्रदान करके)।<br/>[`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient) की कोई भी इम्प्लीमेंटेशन उपयोग की जा सकती है, जिसमें शामिल हैं:<br/><br/>* [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/hi/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ निर्मित [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient) का उपयोग करने के लिए,<br/>इसके बजाय **SlidesAIAgent.#ctor** ओवरलोड का उपयोग करें। |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent/__init__/#) | [`SlidesAIAgent`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent) का नया उदाहरण निर्मित [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient) का उपयोग करके डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ आरंभ करता है।<br/>क्लाइंट Aspose के अपने LLM से जुड़ता है और अतिरिक्त कॉन्फ़िगरेशन की आवश्यकता नहीं होती।<br/>विभिन्न AI क्लाइंट का उपयोग करने के लिए, **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** ओवरलोड का उपयोग करें। |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | पाठ विवरण से एक प्रेजेंटेशन इंस्टेंस उत्पन्न करता है। आवश्यक भाषा में विषय, विचार, उद्धरण, या टेक्स्ट स्निपेट प्रदान करें। |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | पाठ विवरण से एक प्रेजेंटेशन इंस्टेंस उत्पन्न करता है। आवश्यक भाषा में विषय, विचार, उद्धरण, या टेक्स्ट स्निपेट प्रदान करें। |
| [`translate(self, presentation, language)`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | AI का उपयोग करके (सिंक्रोनस संस्करण) प्रेजेंटेशन को निर्दिष्ट भाषा में अनुवादित करता है। |

### देखें
* क्लास [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)
* क्लास [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient)
* क्लास [`OpenAICompatibleWebClient`](/slides/python-net/hi/aspose.slides.ai/openaicompatiblewebclient)
* क्लास [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)
* क्लास [`SlidesAIAgent`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent)
* मॉड्यूल [`aspose.slides.ai`](/slides/python-net/hi/aspose.slides.ai)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)