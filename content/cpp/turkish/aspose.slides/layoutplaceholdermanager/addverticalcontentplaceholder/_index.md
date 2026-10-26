---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides için C++ API Referansı
description: Dikey yönde bir resim, tablo, medya veya metin gibi içeriği tutmak için layout slaytına yeni bir placeholder şekli ekler.
type: docs
weight: 14
url: /tr/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) method


Yeni bir placeholder şekli ekler layout slaytına, içerik tutmak için; örneğin bir resim, tablo, medya ya da metin dikey yönde.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni placeholder şeklinin X koordinatı. |
| y | **float** | Yeni placeholder şeklinin Y koordinatı. |
| width | **float** | Yeni placeholder şeklinin genişliği. |
| height | **float** | Yeni placeholder şeklinin yüksekliği. |

### Dönüş Değeri

[IAutoShape](../../iautoshape/) bir Content (Vertical) placeholder ile oluşturuldu.
## Açıklamalar



Aşağıdaki örnek, Content (Vertical) placeholder şeklinin layout slaytına nasıl ekleneceğini gösterir.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)