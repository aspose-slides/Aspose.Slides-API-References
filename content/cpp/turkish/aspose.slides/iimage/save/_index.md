---
title: Save()
second_title: Aspose.Slides for C++ API Referansı
description: Görüntüyü bir dosyaya kaydeder.
type: docs
weight: 40
url: /tr/aspose.slides/iimage/save/
---
## IImage::Save(System::String) metodu


Görüntüyü bir dosyaya kaydeder.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Görüntünün kaydedileceği dosyanın yolu. |

## IImage::Save(System::String, ImageFormat) metodu


Görüntüyü belirtilen biçimde bir dosyaya kaydeder.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Görüntünün kaydedileceği dosyanın yolu. |
| format | [ImageFormat](../../imageformat/) | Görüntü biçimi. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) metodu


Görüntüyü belirtilen biçimde bir akışa kaydeder.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Görüntünün kaydedileceği akış. |
| format | [ImageFormat](../../imageformat/) | Görüntü biçimi. |

## IImage::Save(System::String, ImageFormat, int32_t) metodu


Görüntüyü belirtilen biçimde ve kaliteyle bir dosyaya kaydeder.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Görüntünün kaydedileceği dosyanın yolu. |
| format | [ImageFormat](../../imageformat/) | Görüntü biçimi. |
| quality | **int32_t** | Kaydedilen görüntünün kalitesi (0 ile 100 arasında). 

 Bu parametre yalnızca [ImageFormat::Jpeg](../../imageformat/) kaydetmeyi etkiler; diğer tüm biçimler için yoksayılır. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) metodu


Görüntüyü belirtilen biçimde ve kaliteyle bir akışa kaydeder.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Görüntünün kaydedileceği akış. |
| format | [ImageFormat](../../imageformat/) | Görüntü biçimi. |
| quality | **int32_t** | Kaydedilen görüntünün kalitesi (0 ile 100 arasında). 

 Bu parametre yalnızca [ImageFormat::Jpeg](../../imageformat/) kaydetmeyi etkiler; diğer tüm biçimler için yoksayılır. |

## İlgili

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IImage](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)