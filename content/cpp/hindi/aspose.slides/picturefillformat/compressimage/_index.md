---
title: CompressImage()
second_title: Aspose.Slides for C++ API संदर्भ
description: छवि को आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर उसके आकार को घटाकर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है।
type: docs
weight: 443
url: /hi/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) विधि

इसे छवि को आकार और निर्दिष्ट समाधान के आधार पर उसके आकार को घटाकर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है।

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | यदि true हो, तो इस विधि द्वारा छवि के क्रॉप किए गए क्षेत्रों को हटाया जाएगा, जिससे उसका आकार और भी घट सकता है। |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | संपीड़न के लिए लक्षित समाधान, जो [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) enum के मान के रूप में निर्दिष्ट है। |

### रिटर्न मान

एक **bool** जो दर्शाता है कि क्या छवि सफलतापूर्वक संकुचित हुई। लौटाती है ****true****

## टिप्पणियाँ

यह विधि छवि के आकार और समाधान को PowerPoint की "Picture Format -> Compress Pictures" सुविधा के समान बदलती है।

यदि छवि का आकार बदला या क्रॉप किया गया हो, अन्यथा ****false****

.

निम्न उदाहरण दर्शाता है कि **CompressImage** विधि का उपयोग करके प्रस्तुति में छवि का आकार कैसे घटाया जाए, लक्षित समाधान सेट करके और क्रॉप किए गए क्षेत्रों को हटाकर:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// छवि को 150 DPI (वेब रिज़ॉल्यूशन) के लक्ष्य समाधान के साथ संकुचित करें और क्रॉप किए गए क्षेत्रों को हटाएँ
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) विधि

इसे छवि को आकार और निर्दिष्ट समाधान के आधार पर उसके आकार को घटाकर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है।

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | यदि true हो, तो इस विधि द्वारा छवि के क्रॉप किए गए क्षेत्रों को हटाया जाएगा, जिससे उसका आकार और भी घट सकता है। |
| resolution | **float** | DPI में लक्षित समाधान। यह मान सकारात्मक होना चाहिए और निर्धारित करता है कि छवि का आकार कैसे बदला जाएगा। |

### रिटर्न मान

एक **bool** जो दर्शाता है कि क्या छवि सफलतापूर्वक संकुचित हुई। लौटाती है ****true****

## टिप्पणियाँ

यह विधि छवि के आकार और समाधान को PowerPoint की "Picture Format -> Compress Pictures" सुविधा के समान बदलती है।

यदि छवि का आकार बदला या क्रॉप किया गया हो, अन्यथा ****false****

.

निम्न उदाहरण दर्शाता है कि **CompressImage** विधि का उपयोग करके प्रस्तुति में छवि का आकार कैसे घटाया जाए, लक्षित समाधान सेट करके और क्रॉप किए गए क्षेत्रों को हटाकर:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame प्राप्त करता है
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// 150 DPI (वेब रिज़ॉल्यूशन) के लक्ष्य समाधान के साथ छवि को संकुचित करें और क्रॉप किए गए क्षेत्रों को हटाएँ
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // वेब रिज़ॉल्यूशन
```

## देखें

* एनम [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* क्लास [PictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)