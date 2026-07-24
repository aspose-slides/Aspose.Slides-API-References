---
title: AddAudioFrameLinked()
second_title: Aspose.Slides için C++ API Referansı
description: Harici bir ses dosyasına bağlanan yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 222
url: /tr/aspose.slides/ishapecollection/addaudioframelinked/
---
## IShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) yöntemi

Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| fname | [System::String](../../../system/string/) | Bağlantı yapılacak harici ses dosyasının yolu veya adı. |

### Dönüş Değeri

Yeni oluşturulan [IAudioFrame](../../iaudioframe/).

## İlgili Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudioFrame](../../iaudioframe/)
* Sınıf [String](../../../system/string/)
* Sınıf [IShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)