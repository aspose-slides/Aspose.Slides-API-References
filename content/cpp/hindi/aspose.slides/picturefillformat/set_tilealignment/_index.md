---
title: set_TileAlignment()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सेट करता है कि टेक्स्चर आकार के भीतर कैसे संरेखित किया गया है। यह सेटिंग टेक्स्चर पैटर्न की शुरुआती बिंदु और यह आकार में कैसे दोहराया जाता है, को नियंत्रित करती है। लिखें RectangleAlignment।
type: docs
weight: 391
url: /hi/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) मेथड


सेट करता है कि टेक्सचर आकार के भीतर कैसे संरेखित किया गया है। यह सेटिंग टेक्सचर पैटर्न की प्रारंभिक बिंदु और यह आकार में कैसे दोहराया जाता है, को नियंत्रित करती है। लिखें [RectangleAlignment](../../rectanglealignment/)।

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## टिप्पणियाँ


डिफ़ॉल्ट [RectangleAlignment::TopLeft](../../rectanglealignment/) है। 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// shape का picture fill format प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// picture fill mode को Tile पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टाइलिंग के संरेखण को दाएँ नीचे सेट करता है
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## देखें भी

* Enum [RectangleAlignment](../../rectanglealignment/)
* क्लास [PictureFillFormat](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)