---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides for C++ API संदर्भ
description: फ़िल Picture के क्रॉप किए गए क्षेत्रों को हटाएँ।
type: docs
weight: 430
url: /hi/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() मेथड

फ़िल [Picture](../../picture/) के क्रॉप किए गए क्षेत्रों को हटाएँ।

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### रिटर्न वैल्यू

यदि क्रॉपिंग आवश्यक नहीं है तो क्रॉप की गई छवि या मूल छवि।

## टिप्पणी

यह मेथड WMF/EMF मेटाफाइलों को रैस्टर PNG छवि में बदलता है जबकि क्रॉप करता है।

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame प्राप्त करता है
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// PictureFrame छवि के क्रॉप किए गए क्षेत्रों को हटाता है
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)