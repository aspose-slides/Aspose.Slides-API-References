---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides için C++ API Referansı
description: Düzen slaytına çevrimiçi bir görüntü tutmak için yeni bir yer tutucu şekil ekler.
type: docs
weight: 118
url: /tr/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) yöntemi

Düzen slaytına çevrimiçi bir görüntü tutmak için yeni bir yer tutucu şekil ekler.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni yer tutucu şeklin X koordinatı. |
| y | **float** | Yeni yer tutucu şeklin Y koordinatı. |
| width | **float** | Yeni yer tutucu şeklin genişliği. |
| height | **float** | Yeni yer tutucu şeklin yüksekliği. |

### Dönüş Değeri

[IAutoShape](../../iautoshape/) oluşturuldu, Online Image yer tutucusu ile.

## Açıklamalar

Aşağıdaki örnek, Online Image yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [LayoutPlaceholderManager](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)