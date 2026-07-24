---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizinde shape collection içine ekler.
type: docs
weight: 196
url: /tr/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metodu


Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizinde shape collection içine ekler.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | OLE nesne çerçevesinin ekleneceği sıfır tabanlı dizin. |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, point cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, point cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, point cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, point cinsinden. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Gömülü OLE veri bilgisi ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Dönüş Değeri

Yeni oluşturulan [IOleObjectFrame](../../ioleobjectframe/).

## Açıklamalar



Bu örnek, ikinci dizinde bir OLE nesnesi eklemeyi göstermektedir: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metodu


Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizinde shape collection içine ekler.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | OLE nesne çerçevesinin ekleneceği sıfır tabanlı dizin. |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, point cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, point cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, point cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, point cinsinden. |
| className | [System::String](../../../system/string/) | OLE nesnesinin sınıf adı. |
| path | [System::String](../../../system/string/) | Bağlantılı dosyanın yolu. |

### Dönüş Değeri

Yeni oluşturulan OLE nesne çerçevesi.

## Açıklamalar



Bu yol, sunumda olduğu gibi saklanır. Göreli bir yol belirtilirse, sunum farklı bir dizinden açıldığında dosyaya erişilemez.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)