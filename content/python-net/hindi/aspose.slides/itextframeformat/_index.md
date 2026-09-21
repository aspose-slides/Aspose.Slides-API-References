---
title: ITextFrameFormat class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/itextframeformat/
---
## ITextFrameFormat क्लास

TextFrame की स्वरूपण गुणों को सम्मिलित करता है।

ITextFrameFormat प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

## Properties

| गुण | विवरण |
| :- | :- |
| [`text_style`](/slides/python-net/hi/aspose.slides/itextframeformat/text_style/) | TextFrame की शैली लौटाता है।<br/>            केवल-पढ़ने योग्य [`ITextStyle`](/slides/python-net/hi/aspose.slides/itextstyle)। |
| [`margin_left`](/slides/python-net/hi/aspose.slides/itextframeformat/margin_left/) | TextFrame में बायाँ मार्जिन (पॉइंट्स) लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **float**। |
| [`margin_right`](/slides/python-net/hi/aspose.slides/itextframeformat/margin_right/) | TextFrame में दायाँ मार्जिन (पॉइंट्स) लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **float**। |
| [`margin_top`](/slides/python-net/hi/aspose.slides/itextframeformat/margin_top/) | TextFrame में ऊपर मार्जिन (पॉइंट्स) लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **float**। |
| [`margin_bottom`](/slides/python-net/hi/aspose.slides/itextframeformat/margin_bottom/) | TextFrame में नीचे मार्जिन (पॉइंट्स) लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **float**। |
| [`wrap_text`](/slides/python-net/hi/aspose.slides/itextframeformat/wrap_text/) | यदि TextFrame की सीमाओं पर टेक्स्ट लपेटा गया है तो **True**।<br/>            पढ़ें/लिखें [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool)। |
| [`anchoring_type`](/slides/python-net/hi/aspose.slides/itextframeformat/anchoring_type/) | TextFrame में वर्टिकल एंकर टेक्स्ट लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें [`TextAnchorType`](/slides/python-net/hi/aspose.slides/textanchortype)। |
| [`center_text`](/slides/python-net/hi/aspose.slides/itextframeformat/center_text/) | यदि NullableBool.True है तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए।<br/>            पढ़ें/लिखें [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool)। |
| [`text_vertical_type`](/slides/python-net/hi/aspose.slides/itextframeformat/text_vertical_type/) | टेक्स्ट अभिविन्यास निर्धारित करता है।<br/>            इस गुण और कस्टम कोण (RotationAngle गुण) से संक्षिप्त दृश्य टेक्स्ट घुमाव का परिणामस्वरूप मान।<br/>            पढ़ें/लिखें [`TextVerticalType`](/slides/python-net/hi/aspose.slides/textverticaltype)। |
| [`autofit_type`](/slides/python-net/hi/aspose.slides/itextframeformat/autofit_type/) | टेक्स्ट के ऑटोफिट मोड को लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें [`TextAutofitType`](/slides/python-net/hi/aspose.slides/textautofittype)। |
| [`column_count`](/slides/python-net/hi/aspose.slides/itextframeformat/column_count/) | टेक्स्ट क्षेत्र में कॉलमों की संख्या लौटाता है या सेट करता है। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान को शून्य किया जाएगा। <br/>            मान 0 अभिभाषित नहीं होने को दर्शाता है।<br/>            पढ़ें/लिखें **int**। |
| [`column_spacing`](/slides/python-net/hi/aspose.slides/itextframeformat/column_spacing/) | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच का अंतराल (पॉइंट्स में) लौटाता है या सेट करता है। यह केवल तब लागू होना चाहिए <br/>            जब 1 से अधिक कॉलम मौजूद हों।<br/>            यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान को शून्य किया जाएगा। <br/>            पढ़ें/लिखें **float**। |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/itextframeformat/three_d_format/) | टेक्स्ट के 3D प्रभाव गुणों को दर्शाने वाला ThreeDFormat ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat)। |
| [`keep_text_flat`](/slides/python-net/hi/aspose.slides/itextframeformat/keep_text_flat/) | टेक्स्ट को पूरी तरह 3D सीन से बाहर रखने को लौटाता है या सेट करता है। पढ़ें/लिखें **bool**। |
| [`rotation_angle`](/slides/python-net/hi/aspose.slides/itextframeformat/rotation_angle/) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम घुमाव को निर्दिष्ट करता है। यदि यह नहीं<br/>            निर्दिष्ट है, तो साथ वाले आकार का घुमाव उपयोग किया जाता है। यदि यह निर्दिष्ट है, तो यह<br/>            आकार से स्वतंत्र रूप से लागू होता है। अर्थात आकार पर घुमाव लागू हो सकता है<br/>            साथ ही टेक्स्ट पर भी घुमाव लागू हो सकता है।<br/>            इस गुण और पूर्वनिर्धारित लंबवत प्रकार (TextVerticalType गुण) से संक्षिप्त दृश्य टेक्स्ट घुमाव का परिणामस्वरूप मान।<br/>            पढ़ें/लिखें **float**। |
| [`transform`](/slides/python-net/hi/aspose.slides/itextframeformat/transform/) | टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`TextShapeType`](/slides/python-net/hi/aspose.slides/textshapetype)। |

## Methods

| मेथड | विवरण |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/hi/aspose.slides/itextframeformat/get_effective/#) | विरासत लागू होने के साथ प्रभावी टेक्स्ट फ्रेम स्वरूपण डेटा प्राप्त करता है। |

### देखें

* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)