---
title: Save()
second_title: Aspose.Slides für C++ API-Referenz
description: Speichert das Bild in einer Datei.
type: docs
weight: 40
url: /de/aspose.slides/iimage/save/
---
## IImage::Save(System::String) Methode

Speichert das Bild in einer Datei.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Der Pfad zur Datei, in der das Bild gespeichert wird. |

## IImage::Save(System::String, ImageFormat) Methode

Speichert das Bild in einer Datei im angegebenen Format.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Der Pfad zur Datei, in der das Bild gespeichert wird. |
| format | [ImageFormat](../../imageformat/) | Das Bildformat. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) Methode

Speichert das Bild in einem Stream im angegebenen Format.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Der Stream, in dem das Bild gespeichert wird. |
| format | [ImageFormat](../../imageformat/) | Das Bildformat. |

## IImage::Save(System::String, ImageFormat, int32_t) Methode

Speichert das Bild in einer Datei im angegebenen Format und Qualität.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Der Pfad zur Datei, in der das Bild gespeichert wird. |
| format | [ImageFormat](../../imageformat/) | Das Bildformat. |
| quality | **int32_t** | Die Qualität des gespeicherten Bildes (0 bis 100). 

 Dieser Parameter wirkt sich nur beim Speichern in [ImageFormat::Jpeg](../../imageformat/) aus; für alle anderen Formate wird er ignoriert. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) Methode

Speichert das Bild in einem Stream im angegebenen Format und Qualität.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Der Stream, in dem das Bild gespeichert wird. |
| format | [ImageFormat](../../imageformat/) | Das Bildformat. |
| quality | **int32_t** | Die Qualität des gespeicherten Bildes (0 bis 100). 

 Dieser Parameter wirkt sich nur beim Speichern in [ImageFormat::Jpeg](../../imageformat/) aus; für alle anderen Formate wird er ignoriert. |

## Siehe auch

* Aufzählung [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [IImage](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)