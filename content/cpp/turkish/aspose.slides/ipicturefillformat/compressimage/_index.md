---
title: CompressImage()
second_title: Aspose.Slides for C++ API Referansı
description: Görüntüyü, şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu azaltarak sıkıştırır. İsteğe bağlı olarak, kırpılmış bölgeleri de siler.
type: docs
weight: 443
url: /tr/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) yöntemi


Görüntüyü, şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu azaltarak sıkıştırır. İsteğe bağlı olarak, kırpılmış bölgeleri de siler.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Doğru ise, yöntem görüntünün kırpılmış bölgelerini kaldıracak ve potansiyel olarak boyutunu daha da azaltacaktır. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Sıkıştırma için hedef çözünürlük, [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) enum değerı olarak belirtilir. |

### Dönüş Değeri

**bool** türünde, görüntünün başarıyla sıkıştırılıp sıkıştırılmadığını belirten bir değer. Döndürür ****true****

## Açıklamalar


Bu yöntem, PowerPoint'in "Picture Format -> Compress Pictures" özelliğine benzer şekilde görüntünün boyutunu ve çözünürlüğünü değiştirir.


görüntü yeniden boyutlandırıldıysa veya kırpıldıysa, aksi takdirde ****false****


Aşağıdaki örnek, hedef bir çözünürlük belirleyerek ve kırpılmış bölgeleri kaldırarak bir sunumdaki görüntünün boyutunu azaltmak için **CompressImage** yönteminin nasıl kullanılacağını gösterir: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Görüntüyü 150 DPI (Web çözünürlüğü) hedef çözünürlük ile sıkıştır ve kırpılmış alanları kaldır
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) yöntemi


Görüntüyü, şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu azaltarak sıkıştırır. İsteğe bağlı olarak, kırpılmış bölgeleri de siler.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Doğru ise, yöntem görüntünün kırpılmış bölgelerini kaldıracak ve potansiyel olarak boyutunu daha da azaltacaktır. |
| resolution | **float** | DPI cinsinden. Bu değer pozitif olmalıdır ve görüntünün nasıl yeniden boyutlandırılacağını tanımlar. |

### Dönüş Değeri

**bool** türünde, görüntünün başarıyla sıkıştırılıp sıkıştırılmadığını belirten bir değer. Döndürür ****true****

## Açıklamalar


Bu yöntem, PowerPoint'in "Picture Format -> Compress Pictures" özelliğine benzer şekilde görüntünün boyutunu ve çözünürlüğünü değiştirir.


görüntü yeniden boyutlandırıldıysa veya kırpıldıysa, aksi takdirde ****false****


Aşağıdaki örnek, hedef bir çözünürlük belirleyerek ve kırpılmış bölgeleri kaldırarak bir sunumdaki görüntünün boyutunu azaltmak için **CompressImage** yönteminin nasıl kullanılacağını gösterir: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame'i alır
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Görüntüyü 150 DPI (Web çözünürlüğü) hedef çözünürlüğü ile sıkıştır ve kırpılmış alanları kaldır
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Web çözünürlüğü
```

## İlgili

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Sınıf [IPictureFillFormat](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)