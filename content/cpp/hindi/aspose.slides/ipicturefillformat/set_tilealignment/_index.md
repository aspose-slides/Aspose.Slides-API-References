---
title: set_TileAlignment()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सेट करता है कि बनावट आकार के भीतर कैसे संरेखित है। यह सेटिंग बनावट पैटर्न के प्रारम्भिक बिंदु और यह आकार के भीतर कैसे दोहराता है, को नियंत्रित करती है। लिखें RectangleAlignment.
type: docs
weight: 391
url: /hi/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) विधि


सेट करता है कि बनावट आकार के भीतर कैसे संरेखित है। यह सेटिंग बनावट पैटर्न के प्रारम्भिक बिंदु और यह आकार के भीतर कैसे दोहराता है, को नियंत्रित करती है। लिखें [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## टिप्पणियाँ


डिफ़ॉल्ट है [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकृति का पिक्चर फ़िल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टाइलिंग के लिए संरेखण को दाएँ नीचे सेट करता है
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## संबंधित देखें

* Enum [RectangleAlignment](../../rectanglealignment/)
* क्लास [IPictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)