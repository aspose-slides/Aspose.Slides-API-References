---
title: AddConnector()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan şablon stilini kullanarak yeni bir bağlayıcı şekli oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 417
url: /tr/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) yöntem

Yeni bir bağlayıcı şekli oluşturur, varsayılan şablon stilini uygular ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
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

## Notlar

Aşağıdaki örnek, PowerPoint [Presentation](../../presentation/) içinde iki şekil (bir elips ve bir dikdörtgen) arasında bir bağlayıcı (eğik bağlayıcı) eklemenin nasıl yapılacağını gösterir.

```cpp
// Bir PPTX dosyasını temsil eden sunum sınıfının bir örneğini oluşturur
auto input = System::MakeObject<Presentation>();

// Belirli bir slayt için şekiller koleksiyonuna erişir
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Bir Elips otomatik şekli ekler
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Bir Dikdörtgen otomatik şekli ekler
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Bağlayıcı şekli slayt şekil koleksiyonuna ekler
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Şekilleri bağlayıcı kullanarak bağlar
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Şekiller arasındaki otomatik en kısa yolu ayarlayan reroute metodunu çağırır
connector->Reroute();

// Sunumu kaydeder
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) yöntem

Yeni bir bağlayıcı şekli oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
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
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)