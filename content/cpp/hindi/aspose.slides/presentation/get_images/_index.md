---
title: get_Images()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रेजेंटेशन में सभी छवियों का संग्रह लौटाता है। केवल-पढ़नीय IImageCollection.
type: docs
weight: 209
url: /hi/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() मेथड

प्रेजेंटेशन में सभी छवियों का संग्रह लौटाता है। केवल-पढ़नीय [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## टिप्पणी

निम्न उदाहरण दिखाते हैं कि PowerPoint में छवि को BLOB के रूप में कैसे जोड़ें [Presentation](../).
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// एक नया प्रेजेंटेशन बनाता है जिसमें छवि जोड़ी जाएगी।
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// आइए छवि को प्रेजेंटेशन में जोड़ें - हम KeepLocked व्यवहार चुनते हैं क्योंकि हम
// इसे "largeImage.png" फ़ाइल तक पहुँचने का इरादा नहीं रखते।
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// प्रेजेंटेशन को सहेजता है। जबकि एक बड़ी प्रेजेंटेशन आउटपुट होती है, मेमोरी उपयोग
// pres ऑब्जेक्ट के जीवनचक्र में कम रहता है।
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण PowerPoint में एक छवि में हाइपरलिंक जोड़ते हैं [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// प्रेजेंटेशन में छवि जोड़ता है
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// पहले जोड़ी गई छवि के आधार पर स्लाइड 1 पर पिक्चर फ्रेम बनाता है
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImageCollection](../../iimagecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)