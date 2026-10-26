---
title: IAudio class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iaudio/
---
## IAudio वर्ग

एक एम्बेडेड ऑडियो फ़ाइल का प्रतिनिधित्व करता है।

IAudio प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/hi/aspose.slides/iaudio/content_type/) | एक ऑडियो की MIME प्रकार लौटाता है, जो [`IAudio.binary_data`](/slides/python-net/hi/aspose.slides/iaudio/binary_data) में एन्कोड किया गया है।<br/>            केवल पढ़ने योग्य **str**. |
| [`binary_data`](/slides/python-net/hi/aspose.slides/iaudio/binary_data/) | ऑडियो के डेटा की प्रतिलिपि लौटाता है। बड़ी मात्रा में डेटा के मामले में, अनावश्यक रूप से ऑडियो के<br/>            डेटा को मेमोरी में लोड करने या OutOfMemoryException होने से बचने के लिए [`IAudio.get_stream`](/slides/python-net/hi/aspose.slides/iaudio/get_stream) मेथड का प्रयोग करने पर विचार करें।<br/>            केवल पढ़ने योग्य **int**[]. |

## विधियाँ

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/hi/aspose.slides/iaudio/get_stream/#) | पढ़ने के लिए Stream स्ट्रीम लौटाता है।<br/>            'using' का उपयोग करें या उपयोग के बाद स्ट्रीम बंद करें. |


### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)