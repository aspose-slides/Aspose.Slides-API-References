---
title: FillPie()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट ब्रश का उपयोग करके निर्दिष्ट पाई को भरता है।
type: docs
weight: 274
url: /hi/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट ब्रश का उपयोग करके निर्दिष्ट पाई को भरता है।

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | पाई को भरते समय उपयोग करने के लिए एक brush |
| x | int | ellipse को परिभाषित करने वाले rectangle के ऊपर बाएँ कोने का X निर्देशांक |
| y | int | ellipse को परिभाषित करने वाले rectangle के ऊपर बाएँ कोने का Y निर्देशांक |
| width | int | ellipse को परिभाषित करने वाले rectangle की चौड़ाई |
| height | int | ellipse को परिभाषित करने वाले rectangle की ऊँचाई |
| startAngle | int | X अक्ष से पाई के प्रारम्भ बिंदु तक घड़ी की दिशा में मापा गया डिग्री में **startAngle** |
| sweepAngle | int | **startAngle** से पाई के समाप्ति बिंदु तक घड़ी की दिशा में मापा गया डिग्री में कोण |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट ब्रश का उपयोग करके निर्दिष्ट पाई को भरता है।

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | पाई को भरते समय उपयोग करने के लिए एक brush |
| x | **float** | ellipse को परिभाषित करने वाले rectangle के ऊपर बाएँ कोने का X निर्देशांक |
| y | **float** | ellipse को परिभाषित करने वाले rectangle के ऊपर बाएँ कोने का Y निर्देशांक |
| width | **float** | ellipse को परिभाषित करने वाले rectangle की चौड़ाई |
| height | **float** | ellipse को परिभाषित करने वाले rectangle की ऊँचाई |
| startAngle | **float** | X अक्ष से पाई के प्रारम्भ बिंदु तक घड़ी की दिशा में मापा गया डिग्री में **startAngle** |
| sweepAngle | **float** | **startAngle** से पाई के समाप्ति बिंदु तक घड़ी की दिशा में मापा गया डिग्री में कोण |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए सतह पर निर्दिष्ट ब्रश का उपयोग करके निर्दिष्ट पाई को भरता है।

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | पाई को भरते समय उपयोग करने के लिए एक brush |
| rect | [Rectangle](../../rectangle/) | ellipse को परिभाषित करने वाला rectangle |
| startAngle | **float** | X अक्ष से पाई के प्रारम्भ बिंदु तक घड़ी की दिशा में मापा गया डिग्री में **startAngle** |
| sweepAngle | **float** | **startAngle** से पाई के समाप्ति बिंदु तक घड़ी की दिशा में मापा गया डिग्री में कोण |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Brush](../../brush/)
* क्लास [Graphics](../)
* क्लास [Rectangle](../../rectangle/)
* नेमस्पेस [System::Drawing](../../)
* Library [Aspose.Slides](../../../)