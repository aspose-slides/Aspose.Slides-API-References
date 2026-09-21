---
title: TextFrameFormat class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/textframeformat/
---
## TextFrameFormat क्लास

TextFrame के formatTextFrameFormatting गुणों को शामिल करता है।

**विरासत:**[`TextFrameFormat`](/slides/python-net/hi/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)

TextFrameFormat प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides/textframeformat/__init__/#) | नए [`TextFrameFormat`](/slides/python-net/hi/aspose.slides/textframeformat) क्लास का एक नया इंस्टैंस इनिशियलाइज़ करता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/textframeformat/three_d_format/) | एक ThreeDFormat वस्तु को लौटाता है जो टेक्स्ट के लिए 3d इफ़ेक्ट गुणों को दर्शाता है।<br/>            केवल-पठनीय [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/hi/aspose.slides/textframeformat/margin_left/) | टेक्टफ़्रेम में बायाँ मार्जिन (पॉइंट्स) लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`margin_right`](/slides/python-net/hi/aspose.slides/textframeformat/margin_right/) | टेक्टफ़्रेम में दायाँ मार्जिन (पॉइंट्स) लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`margin_top`](/slides/python-net/hi/aspose.slides/textframeformat/margin_top/) | टेक्टफ़्रेम में ऊपरी मार्जिन (पॉइंट्स) लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`margin_bottom`](/slides/python-net/hi/aspose.slides/textframeformat/margin_bottom/) | टेक्टफ़्रेम में निचला मार्जिन (पॉइंट्स) लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`wrap_text`](/slides/python-net/hi/aspose.slides/textframeformat/wrap_text/) | **True** यदि टेक्स्ट TextFrame के मार्जिन पर रैप्ड है।<br/>            पढ़ें/लिखें [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/hi/aspose.slides/textframeformat/anchoring_type/) | टेक्टफ़्रेम में वर्टिकल एंकर टेक्स्ट लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें [`TextAnchorType`](/slides/python-net/hi/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/hi/aspose.slides/textframeformat/center_text/) | यदि NullableBool.True है तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित होना चाहिए।<br/>            पढ़ें/लिखें [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/hi/aspose.slides/textframeformat/text_vertical_type/) | टेक्स्ट की अभिविन्यास निर्धारित करता है।<br/>            विज़ुअल टेक्स्ट रोटेशन का परिणामस्वरूप मान इस प्रॉपर्टी और कस्टम एंगल प्रॉपर्टी RotationAngle से संक्षिप्त किया गया है।<br/>            पढ़ें/लिखें [`TextVerticalType`](/slides/python-net/hi/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/hi/aspose.slides/textframeformat/autofit_type/) | टेक्स्ट के ऑटोफ़िट मोड को लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें [`TextAutofitType`](/slides/python-net/hi/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/hi/aspose.slides/textframeformat/column_count/) | टेक्स्ट एरिया में कॉलम की संख्या लौटाता है या सेट करता है।<br/>            यह मान सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य सेट किया जाएगा। <br/>            मान 0 अनिर्धारित मान दर्शाता है।<br/>            पढ़ें/लिखें **int**. |
| [`column_spacing`](/slides/python-net/hi/aspose.slides/textframeformat/column_spacing/) | टेक्स्ट कॉलमों के बीच अंतराल (पॉइंट्स) लौटाता है या सेट करता है। यह केवल तब लागू होना चाहिए जब एक से अधिक कॉलम मौजूद हो।<br/>            यह मान सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य सेट किया जाएगा। <br/>            पढ़ें/लिखें **float**. |
| [`rotation_angle`](/slides/python-net/hi/aspose.slides/textframeformat/rotation_angle/) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन निर्दिष्ट करता है। यदि निर्दिष्ट नहीं है, तो साथ वाले आकार का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट है, तो यह आकार से स्वतंत्र रूप से लागू किया जाता है। अर्थात् आकार पर रोटेशन लागू हो सकता है जबकि टेक्स्ट पर भी अलग रोटेशन लागू हो सकता है।<br/>            विज़ुअल टेक्स्ट रोटेशन का परिणामस्वरूप मान इस प्रॉपर्टी और प्रॉपर्टी TextVerticalType में परिभाषित वर्टिकल टाइप से संक्षिप्त किया गया है।<br/>            पढ़ें/लिखें **float**. |
| [`transform`](/slides/python-net/hi/aspose.slides/textframeformat/transform/) | टेक्स्ट रैपिंग शेप प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें [`TextShapeType`](/slides/python-net/hi/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/hi/aspose.slides/textframeformat/keep_text_flat/) | यदि 3-D रोटेशन प्रभाव लागू किया गया हो तो भी टेक्स्ट को सपाट रखने को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें **bool**. |
| [`slide`](/slides/python-net/hi/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/hi/aspose.slides/textframeformat/text_style/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/hi/aspose.slides/textframeformat/get_effective/#) | विरासत लागू किए गए प्रभावी टेक्स्ट फ्रेम फॉर्मेटिंग डेटा को प्राप्त करता है। |

### संबंधित देखें
* क्लास [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)
* क्लास [`TextFrameFormat`](/slides/python-net/hi/aspose.slides/textframeformat)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)