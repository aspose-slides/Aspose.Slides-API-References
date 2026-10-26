---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 209
url: /tr/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) metod


Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Yeni video çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni video çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni video çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni video çerçevesinin yüksekliği, puan cinsinden. |
| fname | [System::String](../../../system/string/) | Gömülecek video dosyasının yolu veya adı. |

### Dönüş Değeri

Yeni oluşturulan [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metod


Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Yeni video çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni video çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni video çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni video çerçevesinin yüksekliği, puan cinsinden. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Video çerçevesine gömmek için [IVideo](../../ivideo/). |

### Dönüş Değeri

Yeni oluşturulan [IVideoFrame](../../ivideoframe/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IVideoFrame](../../ivideoframe/)
* Sınıf [String](../../../system/string/)
* Sınıf [ShapeCollection](../)
* Sınıf [IVideo](../../ivideo/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)