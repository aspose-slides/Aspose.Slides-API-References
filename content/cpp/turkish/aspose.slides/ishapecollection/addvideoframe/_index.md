---
title: AddVideoFrame()
second_title: C++ için Aspose.Slides API Referansı
description: Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 170
url: /tr/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) yöntem


Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni video çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni video çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni video çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni video çerçevesinin yüksekliği, puan cinsinden. |
| fname | [System::String](../../../system/string/) | Gömülecek video dosyasının yolu veya adı. |

### Dönüş Değeri

Yeni oluşturulan [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) yöntem


Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni video çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni video çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni video çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni video çerçevesinin yüksekliği, puan cinsinden. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [IVideo](../../ivideo/) öğesi, video çerçevesine gömmek için. |

### Dönüş Değeri

Yeni oluşturulan [IVideoFrame](../../ivideoframe/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IVideoFrame](../../ivideoframe/)
* Sınıf [String](../../../system/string/)
* Sınıf [IShapeCollection](../)
* Sınıf [IVideo](../../ivideo/)
* AdAlanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)