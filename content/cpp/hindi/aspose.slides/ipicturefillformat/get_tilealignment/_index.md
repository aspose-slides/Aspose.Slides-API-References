---
title: get_TileAlignment()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वापस करता है कि बनावट आकार के भीतर कैसे संरेखित है। यह सेटिंग बनावट पैटर्न के प्रारंभ बिंदु और यह कि यह आकार के पूरे हिस्से में कैसे दोहराया जाता है, को नियंत्रित करती है। पढ़ें RectangleAlignment.
type: docs
weight: 378
url: /hi/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() विधि

वापस करता है कि बनावट आकार के भीतर कैसे संरेखित है। यह सेटिंग बनावट पैटर्न के प्रारंभ बिंदु और यह कि यह आकार के पूरे हिस्से में कैसे दोहराया जाता है, को नियंत्रित करती है। पढ़ें [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## टिप्पणियाँ

डिफ़ॉल्ट है [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार का चित्र भरने फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र भरने मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टाइलिंग के संरेखण को नीचे दाएँ सेट करता है
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## देखें

* एनम [RectangleAlignment](../../rectanglealignment/)
* क्लास [IPictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)