---
title: InsertConnector()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir bağlayıcı şekli oluşturur ve belirtilen dizine şekil koleksiyonuna ekler, varsayılan şablon stilini uygular.
type: docs
weight: 391
url: /tr/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metot


Yeni bir bağlayıcı şekli oluşturur ve belirtilen dizine şekil koleksiyonuna ekler, varsayılan şablon stilini uygular.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Bağlayıcı şeklinin ekleneceği sıfır tabanlı dizin. |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek bağlayıcı şeklin [ShapeType](../../shapetype/). |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, puan olarak. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, puan olarak. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, puan olarak. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, puan olarak. |

### Dönüş Değeri

Yeni oluşturulan [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metot


Yeni bir bağlayıcı şekli oluşturur ve belirtilen dizine şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Bağlayıcı şeklinin ekleneceği sıfır tabanlı dizin. |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek bağlayıcı şeklin [ShapeType](../../shapetype/). |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, puan olarak. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, puan olarak. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, puan olarak. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, puan olarak. |
| createFromTemplate | **bool** | Varsayılan şablon stilini uygulamak için doğru (boş olmayan ad, basit stil); bağlayıcıyı varsayılan özellik değerleriyle oluşturmak için yanlış. |

### Dönüş Değeri

Yeni oluşturulan [IConnector](../../iconnector/).

## İlgili Bakınız

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IConnector](../../iconnector/)
* Sınıf [IShapeCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)