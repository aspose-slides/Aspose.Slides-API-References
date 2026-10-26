---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. Grubun çerçevesi, eklenen şekillere otomatik olarak uyacak şekilde ayarlanır.
type: docs
weight: 391
url: /tr/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() metodu


Yeni boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. Grubun çerçevesi, içine eklenen şekillere otomatik olarak uyacak şekilde ayarlanır.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Dönüş Değeri

Yeni oluşturulan [IGroupShape](../../igroupshape/).
## Notlar



Aşağıdaki örnek, PowerPoint [Presentation](../../presentation/) bir slayta grup şekli eklemenin nasıl yapıldığını gösterir.
```cpp
// Sunum sınıfını örnekle
auto pres = System::MakeObject<Presentation>();

// İlk slaytı al
auto slide = pres->get_Slides()->idx_get(0);
// Slaytların şekil koleksiyonuna erişme
auto slideShapes = slide->get_Shapes();
// Slayta bir grup şekil ekleme
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Eklenen grup şekli içinde şekiller ekleme
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Grup şekli çerçevesi ekleme
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// PPTX dosyasını diske kaydet
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metodu


Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü ayrı ayrı şekillere dönüştürür ve ortaya çıkan grubu şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) vektör içeriğini içeren ve şekillere dönüştürülecek. |
| x | **float** | Grubun çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Grubun çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Grubun çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Grubun çerçevesinin yüksekliği, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IGroupShape](../../igroupshape/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IGroupShape](../../igroupshape/)
* Sınıf [ShapeCollection](../)
* Sınıf [ISvgImage](../../isvgimage/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)