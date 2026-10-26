---
title: InsertAutoShape()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir otomatik şekil oluşturur ve belirtilen indeks'te şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular.
type: docs
weight: 378
url: /tr/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metod

Yeni bir otomatik şekil oluşturur ve belirtilen indeks'te şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni otomatik şeklin ekleneceği sıfır tabanlı indeks. |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek otomatik şeklin [ShapeType](../../shapetype/). |
| x | **float** | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metod

Yeni bir otomatik şekil oluşturur ve belirtilen indeks'te şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygulayarak başlatır.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Otomatik şeklin ekleneceği sıfır tabanlı indeks. |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek otomatik şeklin [ShapeType](../../shapetype/). |
| x | **float** | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | **bool** | Doğru ise varsayılan şablon stilini uygular (boş olmayan ad, basit stil ve ortalanmış metin dahil); yanlış ise şekli tüm özellikleri varsayılan ayarlara sahip olarak oluşturur. |

### Dönüş Değeri

Yeni oluşturulan [IAutoShape](../../iautoshape/).

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [ShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)