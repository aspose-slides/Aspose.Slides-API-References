---
title: DrawImage()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: अभी लागू नहीं किया गया।
type: docs
weight: 430
url: /hi/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) विधि


अभी लागू नहीं किया गया।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORED |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORED |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि का निर्दिष्ट क्षेत्र ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | एक एरे जिसमें तीन बिंदु होते हैं जो ड्रॉइंग सतह पर एक पैरेललोग्राम परिभाषित करते हैं जिस पर छवि को ड्रॉ किया जाएगा |
| srcRect | const [RectangleF](../../rectanglef/)\& | एक आयत जो निर्दिष्ट छवि के ड्रॉ करने के क्षेत्र को परिभाषित करती है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** पैरामीटर द्वारा उपयोग की जाने वाली मापन इकाइयाँ |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | छवि के लिए रंगीनकरण और गामा जानकारी निर्दिष्ट करता है |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि का निर्दिष्ट क्षेत्र ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | एक एरे व्यू जिसमें तीन बिंदु होते हैं जो ड्रॉइंग सतह पर एक पैरेललोग्राम परिभाषित करते हैं जिस पर छवि को ड्रॉ किया जाएगा |
| srcRect | const [RectangleF](../../rectanglef/)\& | एक आयत जो निर्दिष्ट छवि के ड्रॉ करने के क्षेत्र को परिभाषित करती है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** पैरामीटर द्वारा उपयोग की जाने वाली मापन इकाइयाँ |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | छवि के लिए रंगीनकरण और गामा जानकारी निर्दिष्ट करता है |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि का निर्दिष्ट क्षेत्र ड्रॉ करता है।

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | एक स्टैक एरे जिसमें तीन बिंदु होते हैं जो ड्रॉइंग सतह पर एक पैरेललोग्राम परिभाषित करते हैं जिस पर छवि को ड्रॉ किया जाएगा |
| srcRect | const [RectangleF](../../rectanglef/)\& | एक आयत जो निर्दिष्ट छवि के ड्रॉ करने के क्षेत्र को परिभाषित करती है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** पैरामीटर द्वारा उपयोग की जाने वाली मापन इकाइयाँ |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | छवि के लिए रंगीनकरण और गामा जानकारी निर्दिष्ट करता है |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| x | int | ड्रॉ की गई छवि के ऊपर बाएँ कोने का X निर्देशांक |
| y | int | ड्रॉ की गई छवि के ऊपर बाएँ कोने का Y निर्देशांक |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| x | **float** | ड्रॉ की गई छवि के ऊपर बाएँ कोने का X निर्देशांक |
| y | **float** | ड्रॉ की गई छवि के ऊपर बाएँ कोने का Y निर्देशांक |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| pt | [Point](../../point/) | ड्रॉ की गई छवि के ऊपर बाएँ कोने का स्थान |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| pt | [PointF](../../pointf/) | ड्रॉ की गई छवि के ऊपर बाएँ कोने का स्थान |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) विधि


निर्दिष्ट आयत में निर्दिष्ट छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| x | int | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने का X निर्देशांक |
| y | int | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने का Y निर्देशांक |
| width | int | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने की चौड़ाई |
| height | int | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने की ऊँचाई |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) विधि


निर्दिष्ट आयत में निर्दिष्ट छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| x | **float** | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने का X निर्देशांक |
| y | **float** | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने का Y निर्देशांक |
| width | **float** | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने की चौड़ाई |
| height | **float** | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने की ऊँचाई |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि का निर्दिष्ट क्षेत्र ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destRect | [RectangleF](../../rectanglef/) | छवि को ड्रॉ करने वाली आयत |
| srcRect | [RectangleF](../../rectanglef/) | एक आयत जो निर्दिष्ट छवि के ड्रॉ करने के क्षेत्र को परिभाषित करती है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** पैरामीटर द्वारा उपयोग की जाने वाली मापन इकाइयाँ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि का निर्दिष्ट क्षेत्र ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destRect | [Rectangle](../../rectangle/) | छवि को ड्रॉ करने वाली आयत |
| srcRect | [Rectangle](../../rectangle/) | एक आयत जो निर्दिष्ट छवि के ड्रॉ करने के क्षेत्र को परिभाषित करती है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** पैरामीटर द्वारा उपयोग की जाने वाली मापन इकाइयाँ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि का निर्दिष्ट क्षेत्र ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| x | int | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने का X निर्देशांक |
| y | int | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने का Y निर्देशांक |
| srcRect | [Rectangle](../../rectangle/) | एक आयत जो निर्दिष्ट छवि के ड्रॉ करने के क्षेत्र को परिभाषित करती है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** पैरामीटर द्वारा उपयोग की जाने वाली मापन इकाइयाँ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| rect | const [Rectangle](../../rectangle/)\& | छवि को ड्रॉ करने वाली आयत |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| rect | const [RectangleF](../../rectanglef/)\& | छवि को ड्रॉ करने वाली आयत |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) विधि


निर्दिष्ट आयत में निर्दिष्ट छवि को ड्रॉ करने वाले क्षेत्र को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destRect | [Rectangle](../../rectangle/) | छवि को ड्रॉ करने वाली आयत |
| srcX | int | वह आयत का X निर्देशांक जो छवि के उस हिस्से को परिभाषित करता है जिसे ड्रॉ किया जाना है |
| srcY | int | वह आयत का Y निर्देशांक जो छवि के उस हिस्से को परिभाषित करता है जिसे ड्रॉ किया जाना है |
| srcWidth | int | वह आयत की चौड़ाई जो छवि के उस हिस्से को परिभाषित करती है जिसे ड्रॉ किया जाना है |
| srcHeight | int | वह आयत की ऊँचाई जो छवि के उस हिस्से को परिभाषित करती है जिसे ड्रॉ किया जाना है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | पैरामीटर **srcX**, **srcY**, **srcWidth** और **srcHeight** में प्रयुक्त मापन इकाइयाँ |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | छवि के लिए रंगीनकरण और गामा जानकारी निर्दिष्ट करता है |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) विधि


निर्दिष्ट आयत में निर्दिष्ट छवि को ड्रॉ करने वाले क्षेत्र को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destRect | [Rectangle](../../rectangle/) | छवि को ड्रॉ करने वाली आयत |
| srcX | **float** | वह आयत का X निर्देशांक जो छवि के उस हिस्से को परिभाषित करता है जिसे ड्रॉ किया जाना है |
| srcY | **float** | वह आयत का Y निर्देशांक जो छवि के उस हिस्से को परिभाषित करता है जिसे ड्रॉ किया जाना है |
| srcWidth | **float** | वह आयत की चौड़ाई जो छवि के उस हिस्से को परिभाषित करती है जिसे ड्रॉ किया जाना है |
| srcHeight | **float** | वह आयत की ऊँचाई जो छवि के उस हिस्से को परिभाषित करती है जिसे ड्रॉ किया जाना है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | पैरामीटर **srcX**, **srcY**, **srcWidth** और **srcHeight** में प्रयुक्त मापन इकाइयाँ |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | छवि के लिए रंगीनकरण और गामा जानकारी निर्दिष्ट करता है |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) विधि


निर्दिष्ट आयत में निर्धारित भाग के साथ छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destRect | [Rectangle](../../rectangle/) | छवि को ड्रॉ करने वाली आयत |
| srcX | int | वह आयत का X निर्देशांक जो छवि के उस हिस्से को परिभाषित करता है जिसे ड्रॉ किया जाना है |
| srcY | int | वह आयत का Y निर्देशांक जो छवि के उस हिस्से को परिभाषित करता है जिसे ड्रॉ किया जाना है |
| srcWidth | int | वह आयत की चौड़ाई जो छवि के उस हिस्से को परिभाषित करती है जिसे ड्रॉ किया जाना है |
| srcHeight | int | वह आयत की ऊँचाई जो छवि के उस हिस्से को परिभाषित करती है जिसे ड्रॉ किया जाना है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | पैरामीटर **srcX**, **srcY**, **srcWidth** और **srcHeight** में प्रयुक्त मापन इकाइयाँ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) विधि


निर्दिष्ट आयत में निर्धारित भाग के साथ छवि को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destRect | [Rectangle](../../rectangle/) | छवि को ड्रॉ करने वाली आयत |
| srcX | **float** | वह आयत का X निर्देशांक जो छवि के उस हिस्से को परिभाषित करता है जिसे ड्रॉ किया जाना है |
| srcY | **float** | वह आयत का Y निर्देशांक जो छवि के उस हिस्से को परिभाषित करता है जिसे ड्रॉ किया जाना है |
| srcWidth | **float** | वह आयत की चौड़ाई जो छवि के उस हिस्से को परिभाषित करती है जिसे ड्रॉ किया जाना है |
| srcHeight | **float** | वह आयत की ऊँचाई जो छवि के उस हिस्से को परिभाषित करती है जिसे ड्रॉ किया जाना है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | पैरामीटर **srcX**, **srcY**, **srcWidth** और **srcHeight** में प्रयुक्त मापन इकाइयाँ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) विधि


अभी लागू नहीं किया गया।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) विधि


अभी लागू नहीं किया गया।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) विधि


अभी लागू नहीं किया गया।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) विधि


अभी लागू नहीं किया गया।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) विधि


अभी लागू नहीं किया गया।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) विधि


अभी लागू नहीं किया गया।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) विधि


अभी लागू नहीं किया गया।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि का निर्दिष्ट क्षेत्र ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | एक एरे जिसमें तीन बिंदु होते हैं जो ड्रॉइंग सतह पर एक पैरेललोग्राम परिभाषित करते हैं जिस पर छवि को ड्रॉ किया जाएगा |
| srcRect | [Rectangle](../../rectangle/) | एक आयत जो निर्दिष्ट छवि के ड्रॉ करने के क्षेत्र को परिभाषित करती है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** पैरामीटर द्वारा उपयोग की जाने वाली मापन इकाइयाँ |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | छवि के लिए रंगीनकरण और गामा जानकारी निर्दिष्ट करता है |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) विधि


निर्दिष्ट स्थान पर निर्दिष्ट छवि का निर्दिष्ट क्षेत्र ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ड्रॉ करने के लिए छवि |
| x | **float** | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने का X निर्देशांक |
| y | **float** | छवि को ड्रॉ करने वाली आयत के ऊपर बाएँ कोने का Y निर्देशांक |
| srcRect | [RectangleF](../../rectanglef/) | एक आयत जो निर्दिष्ट छवि के ड्रॉ करने के क्षेत्र को परिभाषित करती है |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** पैरामीटर द्वारा उपयोग की जाने वाली मापन इकाइयाँ |

## देखें

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Class [Image](../../image/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)