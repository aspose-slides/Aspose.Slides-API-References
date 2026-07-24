---
title: AddConnector()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir bağlayıcı şekli varsayılan şablon stilinde oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 378
url: /tr/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) metodu

Yeni bir bağlayıcı şekli varsayılan şablon stilinde oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Eklenecek bağlayıcı şeklin [ShapeType](../../shapetype/). |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metodu

Yeni bir bağlayıcı şekli oluşturur ve isteğe bağlı olarak varsayılan şablon stilini uygulayarak şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Oluşturulacak bağlayıcı şeklin [ShapeType](../../shapetype/). |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | **bool** | Varsayılan şablon stilini uygulamak için true (boş olmayan ad, basit stil); bağlayıcıyı varsayılan özellik değerleriyle oluşturmak için false. |

### Dönüş Değeri

Yeni oluşturulan [IConnector](../../iconnector/).

## Ayrıca Bakınız

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)