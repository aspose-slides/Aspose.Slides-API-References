---
title: AddGroupShape()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. Grubun çerçevesi, eklenen şekillere otomatik olarak uyacak şekilde ayarlanır.
type: docs
weight: 352
url: /tr/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() metodu


Yeni boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. Grup çerçevesi, eklenen şekillere otomatik olarak uyacak şekilde ayarlanır.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### Dönüş Değeri

Yeni oluşturulan [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metodu


Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü bireysel şekillere dönüştürür ve ortaya çıkan grubu şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Şekillere dönüştürülecek vektör içeriklerini içeren [ISvgImage](../../isvgimage/). |
| x | **float** | Grup çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Grup çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Grup çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Grup çerçevesinin yüksekliği, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IGroupShape](../../igroupshape/).

## İlgili

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IGroupShape](../../igroupshape/)
* Sınıf [IShapeCollection](../)
* Sınıf [ISvgImage](../../isvgimage/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)