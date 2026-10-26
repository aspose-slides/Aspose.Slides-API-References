---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides C++ için API Referansı
description: Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler.
type: docs
weight: 274
url: /tr/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) method


Yeni bir ses çerçevesi oluşturur, harici bir ses dosyasına bağlar ve belirtilen indekste şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Ses çerçevesini ekleyeceğiniz sıfır tabanlı indeks. |
| x | **float** | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| fname | [System::String](../../../system/string/) | Bağlanacak harici ses dosyasının yolu veya adı. |

### Dönüş Değeri

Yeni oluşturulan [IAudioFrame](../../iaudioframe/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudioFrame](../../iaudioframe/)
* Sınıf [String](../../../system/string/)
* Sınıf [ShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)