---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides C++ API Referansı
description: Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.
type: docs
weight: 235
url: /tr/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) yöntemi

Yeni bir harici ses dosyasına bağlı ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Ses çerçevesinin ekleneceği sıfır tabanlı dizin. |
| x | **float** | Yeni ses çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, nokta cinsinden. |
| fname | [System::String](../../../system/string/) | Bağlantı kurulacak harici ses dosyasının yolu veya adı. |

### Dönüş Değeri

Yeni oluşturulan [IAudioFrame](../../iaudioframe/).

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudioFrame](../../iaudioframe/)
* Sınıf [String](../../../system/string/)
* Sınıf [IShapeCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)