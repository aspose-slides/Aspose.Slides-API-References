---
title: Save()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zapisuje obraz do pliku.
type: docs
weight: 40
url: /pl/aspose.slides/iimage/save/
---
## IImage::Save(System::String) metoda

Zapisuje obraz do pliku.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Ścieżka do pliku, w którym zostanie zapisany obraz. |

## IImage::Save(System::String, ImageFormat) metoda

Zapisuje obraz do pliku w określonym formacie.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Ścieżka do pliku, w którym zostanie zapisany obraz. |
| format | [ImageFormat](../../imageformat/) | Format obrazu. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) metoda

Zapisuje obraz do strumienia w określonym formacie.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, w którym zostanie zapisany obraz. |
| format | [ImageFormat](../../imageformat/) | Format obrazu. |

## IImage::Save(System::String, ImageFormat, int32_t) metoda

Zapisuje obraz do pliku w określonym formacie i jakości.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Ścieżka do pliku, w którym zostanie zapisany obraz. |
| format | [ImageFormat](../../imageformat/) | Format obrazu. |
| quality | **int32_t** | Jakość zapisanego obrazu (0-100). 

 Ten parametr ma wpływ tylko na zapisywanie w [ImageFormat::Jpeg](../../imageformat/); dla wszystkich innych formatów jest ignorowany. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) metoda

Zapisuje obraz do strumienia w określonym formacie i jakości.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, w którym zostanie zapisany obraz. |
| format | [ImageFormat](../../imageformat/) | Format obrazu. |
| quality | **int32_t** | Jakość zapisanego obrazu (0-100). 

 Ten parametr ma wpływ tylko na zapisywanie w [ImageFormat::Jpeg](../../imageformat/); dla wszystkich innych formatów jest ignorowany. |

## Zobacz także

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [IImage](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)