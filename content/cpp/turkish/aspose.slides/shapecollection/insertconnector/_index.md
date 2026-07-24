---
title: InsertConnector()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir bağlayıcı şekil oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler, varsayılan şablon stilini uygular.
type: docs
weight: 430
url: /tr/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metod

Yeni bir bağlayıcı şekli oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler, varsayılan şablon stilini uygular.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Bağlayıcı şeklin ekleneceği sıfır tabanlı indeks. |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek bağlayıcı şeklin [ShapeType](../../shapetype/). |
| x | **float** | Bağlayıcı çerçevenin x koordinatı, nokta cinsinden. |
| y | **float** | Bağlayıcı çerçevenin y koordinatı, nokta cinsinden. |
| width | **float** | Bağlayıcı çerçevenin genişliği, nokta cinsinden. |
| height | **float** | Bağlayıcı çerçevenin yüksekliği, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IConnector](../../iconnector/).

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metod

Yeni bir bağlayıcı şekli oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Bağlayıcı şeklin ekleneceği sıfır tabanlı indeks. |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek bağlayıcı şeklin [ShapeType](../../shapetype/). |
| x | **float** | Bağlayıcı çerçevenin x koordinatı, nokta cinsinden. |
| y | **float** | Bağlayıcı çerçevenin y koordinatı, nokta cinsinden. |
| width | **float** | Bağlayıcı çerçevenin genişliği, nokta cinsinden. |
| height | **float** | Bağlayıcı çerçevenin yüksekliği, nokta cinsinden. |
| createFromTemplate | **bool** | Varsayılan şablon stilini uygulamak için True (boş olmayan ad, basit stil); bağlayıcıyı varsayılan özellik değerleriyle oluşturmak için false. |

### Dönüş Değeri

Yeni oluşturulan [IConnector](../../iconnector/).

## Ayrıca Bakınız

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IConnector](../../iconnector/)
* Sınıf [ShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)