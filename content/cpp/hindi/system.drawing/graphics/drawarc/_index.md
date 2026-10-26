---
title: DrawArc()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट पेन का उपयोग करके निर्दिष्ट चाप को ड्रॉ करता है।
type: docs
weight: 248
url: /hi/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) मेथड


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट पेन का उपयोग करके निर्दिष्ट चाप को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | चाप को ड्रॉ करने के समय उपयोग करने वाला पेन |
| x | **int32_t** | दीर्घवृत्त को परिभाषित करने वाली आयत के ऊपरी बाएँ कोने का X निर्देशांक |
| y | **int32_t** | दीर्घवृत्त को परिभाषित करने वाली आयत के ऊपरी बाएँ कोने का Y निर्देशांक |
| width | **int32_t** | दीर्घवृत्त को परिभाषित करने वाली आयत की चौड़ाई |
| height | **int32_t** | दीर्घवृत्त को परिभाषित करने वाली आयत की ऊँचाई |
| startAngle | **int32_t** | X-अक्ष से घड़ी की दिशा में मापा गया डिग्री में कोण, जो चाप के प्रारम्भ बिंदु तक है |
| sweepAngle | **int32_t** | **startAngle** से घड़ी की दिशा में मापा गया डिग्री में कोण, जो चाप के अंत बिंदु तक है |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) मेथड


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट पेन का उपयोग करके निर्दिष्ट चाप को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | चाप को ड्रॉ करने के समय उपयोग करने वाला पेन |
| x | **float** | दीर्घवृत्त को परिभाषित करने वाली आयत के ऊपरी बाएँ कोने का X निर्देशांक |
| y | **float** | दीर्घवृत्त को परिभाषित करने वाली आयत के ऊपरी बाएँ कोने का Y निर्देशांक |
| width | **float** | दीर्घवृत्त को परिभाषित करने वाली आयत की चौड़ाई |
| height | **float** | दीर्घवृत्त को परिभाषित करने वाली आयत की ऊँचाई |
| startAngle | **float** | X-अक्ष से घड़ी की दिशा में मापा गया डिग्री में कोण, जो चाप के प्रारम्भ बिंदु तक है |
| sweepAngle | **float** | **startAngle** से घड़ी की दिशा में मापा गया डिग्री में कोण, जो चाप के अंत बिंदु तक है |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) मेथड


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट पेन का उपयोग करके निर्दिष्ट चाप को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | चाप को ड्रॉ करने के समय उपयोग करने वाला पेन |
| rect | [Rectangle](../../rectangle/) | वह आयत जो दीर्घवृत्त को परिभाषित करती है |
| startAngle | **float** | X-अक्ष से घड़ी की दिशा में मापा गया डिग्री में कोण, जो चाप के प्रारम्भ बिंदु तक है |
| sweepAngle | **float** | **startAngle** से घड़ी की दिशा में मापा गया डिग्री में कोण, जो चाप के अंत बिंदु तक है |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) मेथड


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट पेन का उपयोग करके निर्दिष्ट चाप को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | चाप को ड्रॉ करने के समय उपयोग करने वाला पेन |
| rect | [RectangleF](../../rectanglef/) | वह आयत जो दीर्घवृत्त को परिभाषित करती है |
| startAngle | **float** | X-अक्ष से घड़ी की दिशा में मापा गया डिग्री में कोण, जो चाप के प्रारम्भ बिंदु तक है |
| sweepAngle | **float** | **startAngle** से घड़ी की दिशा में मापा गया डिग्री में कोण, जो चाप के अंत बिंदु तक है |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)