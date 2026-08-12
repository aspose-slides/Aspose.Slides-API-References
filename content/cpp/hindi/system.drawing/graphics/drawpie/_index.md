---
title: DrawPie()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट पेन का उपयोग करके निर्दिष्ट पाई को ड्रॉ करता है।
type: docs
weight: 261
url: /hi/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) विधि


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट pen का उपयोग करके निर्दिष्ट pie को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | एक pen जो pie ड्रॉ करने के दौरान उपयोग किया जाता है |
| x | **int32_t** | ellipse को परिभाषित करने वाले आयत के ऊपरी बाएँ कोने की X निर्देशांक |
| y | **int32_t** | ellipse को परिभाषित करने वाले आयत के ऊपरी बाएँ कोने की Y निर्देशांक |
| width | **int32_t** | ellipse को परिभाषित करने वाले आयत की चौड़ाई |
| height | **int32_t** | ellipse को परिभाषित करने वाले आयत की ऊँचाई |
| startAngle | **int32_t** | X अक्ष से घड़ी की दिशा में मापी गई डिग्री में कोण, जो pie के शुरुआती बिंदु को दर्शाता है |
| sweepAngle | **int32_t** | X अक्ष से घड़ी की दिशा में **startAngle** से मापी गई डिग्री में कोण, जो pie के समाप्ति बिंदु को दर्शाता है |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) विधि


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट pen का उपयोग करके निर्दिष्ट pie को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | एक pen जो pie ड्रॉ करने के दौरान उपयोग किया जाता है |
| x | **float** | ellipse को परिभाषित करने वाले आयत के ऊपरी बाएँ कोने की X निर्देशांक |
| y | **float** | ellipse को परिभाषित करने वाले आयत के ऊपरी बाएँ कोने की Y निर्देशांक |
| width | **float** | ellipse को परिभाषित करने वाले आयत की चौड़ाई |
| height | **float** | ellipse को परिभाषित करने वाले आयत की ऊँचाई |
| startAngle | **float** | X अक्ष से घड़ी की दिशा में मापी गई डिग्री में कोण, जो pie के शुरुआती बिंदु को दर्शाता है |
| sweepAngle | **float** | X अक्ष से घड़ी की दिशा में **startAngle** से मापी गई डिग्री में कोण, जो pie के समाप्ति बिंदु को दर्शाता है |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) विधि


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट pen का उपयोग करके निर्दिष्ट pie को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | एक pen जो pie ड्रॉ करने के दौरान उपयोग किया जाता है |
| rect | [Rectangle](../../rectangle/) | ellipse को परिभाषित करने वाला आयत |
| startAngle | **float** | X अक्ष से घड़ी की दिशा में मापी गई डिग्री में कोण, जो pie के शुरुआती बिंदु को दर्शाता है |
| sweepAngle | **float** | X अक्ष से घड़ी की दिशा में **startAngle** से मापी गई डिग्री में कोण, जो pie के समाप्ति बिंदु को दर्शाता है |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) विधि


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट pen का उपयोग करके निर्दिष्ट pie को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | एक pen जो pie ड्रॉ करने के दौरान उपयोग किया जाता है |
| rect | [RectangleF](../../rectanglef/) | ellipse को परिभाषित करने वाला आयत |
| startAngle | **float** | X अक्ष से घड़ी की दिशा में मापी गई डिग्री में कोण, जो pie के शुरुआती बिंदु को दर्शाता है |
| sweepAngle | **float** | X अक्ष से घड़ी की दिशा में **startAngle** से मापी गई डिग्री में कोण, जो pie के समाप्ति बिंदु को दर्शाता है |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Pen](../../pen/)
* क्लास [Graphics](../)
* क्लास [Rectangle](../../rectangle/)
* क्लास [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)