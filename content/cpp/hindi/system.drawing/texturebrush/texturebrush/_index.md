---
title: TextureBrush()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट छवि का उपयोग करने वाली TextureBrush क्लास का एक नया उदाहरण बनाता है।
type: docs
weight: 1
url: /hi/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) constructor

निर्दिष्ट छवि का उपयोग करने वाली [TextureBrush](../) क्लास का एक नया उदाहरण बनाता है।

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ब्रश द्वारा आकार के भीतर भरने के लिए उपयोग की गई छवि |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | निर्धारित करता है कि ब्रश ऑब्जेक्ट कैसे टाइल किया जाता है |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

निर्दिष्ट छवि का उपयोग करने वाली [TextureBrush](../) क्लास का एक नया उदाहरण बनाता है।

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ब्रश द्वारा आकार के भीतर भरने के लिए उपयोग की गई छवि |
| dst_rect | [RectangleF](../../rectanglef/) | ब्रश के लिए बाउंडिंग आयत निर्धारित करता है |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | इमेज एट्रीब्यूट्स |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) constructor

निर्दिष्ट छवि का उपयोग करने वाली [TextureBrush](../) क्लास का एक नया उदाहरण बनाता है।

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ब्रश द्वारा आकार के भीतर भरने के लिए उपयोग की गई छवि |
| dst_rect | [Rectangle](../../rectangle/) | ब्रश के लिए बाउंडिंग आयत निर्धारित करता है |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | इमेज एट्रीब्यूट्स |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) constructor

निर्दिष्ट छवि का उपयोग करने वाली [TextureBrush](../) क्लास का एक नया उदाहरण बनाता है।

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ब्रश द्वारा आकार के भीतर भरने के लिए उपयोग की गई छवि |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | निर्धारित करता है कि ब्रश ऑब्जेक्ट कैसे टाइल किया जाता है |
| dst_rect | [RectangleF](../../rectanglef/) | ब्रश के लिए बाउंडिंग आयत निर्धारित करता है |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) constructor

निर्दिष्ट छवि का उपयोग करने वाली [TextureBrush](../) क्लास का एक नया उदाहरण बनाता है।

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ब्रश द्वारा आकार के भीतर भरने के लिए उपयोग की गई छवि |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | निर्धारित करता है कि ब्रश ऑब्जेक्ट कैसे टाइल किया जाता है |
| dst_rect | [Rectangle](../../rectangle/) | ब्रश के लिए बाउंडिंग आयत निर्धारित करता है |

## संबंधित देखें

* एन्यूम [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Image](../../image/)
* क्लास [TextureBrush](../)
* क्लास [RectangleF](../../rectanglef/)
* क्लास [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* क्लास [Rectangle](../../rectangle/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)