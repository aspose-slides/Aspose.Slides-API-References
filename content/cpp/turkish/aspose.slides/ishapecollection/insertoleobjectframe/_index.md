---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.
type: docs
weight: 79
url: /tr/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metodu


Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | OLE nesne çerçevesinin ekleneceği sıfır tabanlı dizin. |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Gömülü OLE veri bilgisi ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Dönüş Değeri

Yeni oluşturulan [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metodu


Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | OLE nesne çerçevesinin ekleneceği sıfır tabanlı dizin. |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| className | [System::String](../../../system/string/) | OLE nesnesinin sınıf adı. |
| path | [System::String](../../../system/string/) | Bağlantılı dosyanın yolu. |

### Dönüş Değeri

Yeni oluşturulan [IOleObjectFrame](../../ioleobjectframe/).

## Açıklamalar



Bu yol, sunumda olduğu gibi saklanır. Göreli bir yol belirtilirse, sunum farklı bir dizinden açıldığında dosyaya erişilemez.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IOleObjectFrame](../../ioleobjectframe/)
* Sınıf [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Sınıf [IShapeCollection](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)