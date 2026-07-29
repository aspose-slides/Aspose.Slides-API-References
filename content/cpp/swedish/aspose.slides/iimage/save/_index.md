---
title: Save()
second_title: Aspose.Slides för C++ API-referens
description: Sparar bilden till en fil.
type: docs
weight: 40
url: /sv/aspose.slides/iimage/save/
---
## IImage::Save(System::String) metod

Sparar bilden till en fil.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Sökvägen till filen där bilden kommer att sparas. |

## IImage::Save(System::String, ImageFormat) metod

Sparar bilden till en fil i angivet format.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Sökvägen till filen där bilden kommer att sparas. |
| format | [ImageFormat](../../imageformat/) | Bildformatet. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) metod

Sparar bilden till en ström i angivet format.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strömmen där bilden kommer att sparas. |
| format | [ImageFormat](../../imageformat/) | Bildformatet. |

## IImage::Save(System::String, ImageFormat, int32_t) metod

Sparar bilden till en fil i angivet format och kvalitet.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Sökvägen till filen där bilden kommer att sparas. |
| format | [ImageFormat](../../imageformat/) | Bildformatet. |
| quality | **int32_t** | Kvaliteten på den sparade bilden (0 till 100).

 Denna parameter påverkar endast sparande i [ImageFormat::Jpeg](../../imageformat/); för alla andra format ignoreras den. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) metod

Sparar bilden till en ström i angivet format och kvalitet.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strömmen där bilden kommer att sparas. |
| format | [ImageFormat](../../imageformat/) | Bildformatet. |
| quality | **int32_t** | Kvaliteten på den sparade bilden (0 till 100).

 Denna parameter påverkar endast sparande i [ImageFormat::Jpeg](../../imageformat/); för alla andra format ignoreras den. |

## Se även

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [IImage](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)