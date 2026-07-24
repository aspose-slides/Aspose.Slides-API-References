---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun sonuna WebVTT kapalı altyazı ekler.
type: docs
weight: 27
url: /tr/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) metodu


Koleksiyonun sonuna WebVTT kapalı altyazı ekler.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Kapalı altyazıların etiketi. |
| filePath | [System::String](../../../system/string/) | WebVTT dosyasının yolu. |

### Return Value

Eklenen [ICaptions](../../icaptions/) örneği.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metodu


Koleksiyonun sonuna bir akıştan WebVTT kapalı altyazı ekler.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Kapalı altyazıların etiketi. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | WebVTT formatındaki verileri içeren giriş akışı. |

### Return Value

Eklenen [ICaptions](../../icaptions/) örneği.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ICaptions](../../icaptions/)
* Sınıf [String](../../../system/string/)
* Sınıf [ICaptionsCollection](../)
* Sınıf [Stream](../../../system.io/stream/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)