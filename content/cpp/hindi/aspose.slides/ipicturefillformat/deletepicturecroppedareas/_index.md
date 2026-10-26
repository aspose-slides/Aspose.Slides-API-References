---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides for C++ API संदर्भ
description: फ़िल चित्र के क्रॉप किए गए क्षेत्रों को हटाएँ।
type: docs
weight: 430
url: /hi/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() विधि


फ़िल [Picture](../../picture/) के क्रॉप किए गए क्षेत्रों को हटाएँ।

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### रिटर्न वैल्यू

क्रॉप किया गया चित्र, यदि क्रॉपिंग आवश्यक नहीं है तो मूल चित्र।
## टिप्पणियाँ


यह विधि WMF/EMF मेटाफाइलों को रास्टर PNG चित्र में बदलती है जबकि क्रॉप करती है।



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame को प्राप्त करता है
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// PictureFrame छवि के क्रॉप किए गए क्षेत्रों को हटाता है
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## इसे भी देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPPImage](../../ippimage/)
* क्लास [IPictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)