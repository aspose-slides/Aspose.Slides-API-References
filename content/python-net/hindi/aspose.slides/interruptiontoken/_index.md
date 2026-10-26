---
title: InterruptionToken class
second_title: Aspose.Slides Python के लिये .NET के माध्यम से API Reference
description: 
type: docs
url: /hi/aspose.slides/interruptiontoken/
---
## InterruptionToken वर्ग

यह वर्ग लम्बे समय चलने वाले कार्यों को संकेत देने के लिए उपयोग किए जाने वाले टोकन को दर्शाता है कि क्या बाधा का अनुरोध किया गया था।

InterruptionToken प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`none`](/slides/python-net/hi/aspose.slides/interruptiontoken/none/) | एक खाली बाधा टोकन को दर्शाता है।<br/>            लम्बे समय चलने वाले संचालन इस टोकन का उपयोग करते समय [`InterruptionTokenSource.interrupt`](/slides/python-net/hi/aspose.slides/interruptiontokensource/interrupt) के माध्यम से कभी बाधित नहीं होते। |
| [`is_interruption_requested`](/slides/python-net/hi/aspose.slides/interruptiontoken/is_interruption_requested/) | यदि बाधा का अनुरोध किया गया हो तो **bool**.true लौटाता है। |

## विधियां

| विधि | विवरण |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/hi/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | यदि<br/>            बाधा का अनुरोध किया गया हो तो OperationCanceledException फेंकता है। |


### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)