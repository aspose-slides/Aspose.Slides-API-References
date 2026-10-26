---
title: Add()
second_title: Aspose.Slides C++ API Referansı
description: WebVTT kapalı altyazıları koleksiyonun sonuna ekler.
type: docs
weight: 27
url: /tr/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) metodu

Koleksiyonun sonuna WebVTT kapalı alt yazılarını ekler.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Kapalı alt yazıların etiketi. |
| filePath | [System::String](../../../system/string/) | WebVTT dosyasının yolu. |

### Dönüş Değeri

Eklenen [ICaptions](../../icaptions/) örneği.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metodu

Koleksiyonun sonuna bir akıştan WebVTT kapalı alt yazılarını ekler.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Kapalı alt yazıların etiketi. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | WebVTT formatında veri içeren giriş akışı. |

### Dönüş Değeri

Eklenen [ICaptions](../../icaptions/) örneği.

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ICaptions](../../icaptions/)
* Sınıf [String](../../../system/string/)
* Sınıf [CaptionsCollection](../)
* Sınıf [Stream](../../../system.io/stream/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)