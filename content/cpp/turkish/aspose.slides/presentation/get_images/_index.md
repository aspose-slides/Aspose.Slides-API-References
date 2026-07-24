---
title: get_Images()
second_title: Aspose.Slides için C++ API Referansı
description: Sunumda bulunan tüm görsellerin koleksiyonunu döndürür. Salt-okunur IImageCollection.
type: docs
weight: 209
url: /tr/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() metodu

Sunum içindeki tüm görsellerin koleksiyonunu döndürür. Salt-okunur [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Açıklamalar

Aşağıdaki örnekler, PowerPoint'te görseli BLOB olarak nasıl ekleyeceğinizi gösterir [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// görselin ekleneceği yeni bir sunum oluşturur.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Görseli sunuma ekleyelim - KeepLocked davranışını seçiyoruz çünkü biz
// "largeImage.png" dosyasına erişmeyi NIYET ETMİYORUZ.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Sunumu kaydeder. Büyük bir sunum çıktısı alınırken, bellek tüketimi
// pres nesnesinin yaşam döngüsü boyunca düşük kalır
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
Aşağıdaki örnekler, bir PowerPoint içinde görsele bir hiper bağlantı ekler [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Sunuma görsel ekler
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Daha önce eklenen görsel temelinde slayt 1'de resim çerçevesi oluşturur
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IImageCollection](../../iimagecollection/)
* Sınıf [Presentation](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)