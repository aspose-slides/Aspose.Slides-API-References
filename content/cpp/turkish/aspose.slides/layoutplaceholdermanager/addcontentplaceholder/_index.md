---
title: AddContentPlaceholder()
second_title: Aspose.Slides için C++ API Referansı
description: Düzen slaytına, bir resim, tablo, medya veya metin gibi içeriği tutmak için yeni bir yer tutucu şekil ekler.
type: docs
weight: 1
url: /tr/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metod

Yeni bir yer tutucu şekli ekler layout slaytına içeriği tutmak için, örneğin bir resim, tablo, medya ya da metin.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

[IAutoShape](../../iautoshape/) bir İçerik yer tutucu ile oluşturuldu.
## Açıklamalar



Aşağıdaki örnek, İçerik yer tutucu şeklini layout slaytına nasıl ekleyeceğinizi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)