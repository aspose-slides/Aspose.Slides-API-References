---
title: AddOleObjectFrame()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 66
url: /tr/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) yöntemi


Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, puan cinsinden. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Gömülü OLE veri bilgisi ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Dönüş Değeri

Yeni oluşturulan [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) yöntemi


Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, puan cinsinden. |
| className | [System::String](../../../system/string/) | OLE nesnesinin sınıf adı. |
| path | [System::String](../../../system/string/) | Bağlantılı dosyanın yolu. |

### Dönüş Değeri

Yeni oluşturulan [IOleObjectFrame](../../ioleobjectframe/).

## Açıklamalar



Bu yol sunumda tam olarak saklanır. Göreli bir yol belirtilirse, sunumu farklı bir klasörden açtığınızda dosyaya erişilemez.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IOleObjectFrame](../../ioleobjectframe/)
* Sınıf [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Sınıf [IShapeCollection](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)