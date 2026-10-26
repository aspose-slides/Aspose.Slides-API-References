---
title: get_TileAlignment()
second_title: Aspose.Slides for C++ API संदर्भ
description: वापस करता है कि बनावट आकार के भीतर कैसे संरेखित है। यह सेटिंग बनावट पैटर्न के प्रारम्भिक बिंदु और आकार के पार इसका दोहराव कैसे होता है, इसे नियंत्रित करती है। पढ़ें RectangleAlignment.
type: docs
weight: 378
url: /hi/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() method


वापस करता है कि बनावट आकार के भीतर कैसे संरेखित है। यह सेटिंग बनावट पैटर्न के प्रारम्भिक बिंदु और आकार के पार इसका दोहराव कैसे होता है, इसे नियंत्रित करती है। पढ़ें [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## टिप्पणियाँ


डिफ़ॉल्ट है [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार का चित्र भराव प्रारूप प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र भराव मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टाइलिंग के लिए संरेखण को नीचे दाएँ सेट करता है
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## संबंधित देखें

* Enum [RectangleAlignment](../../rectanglealignment/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)