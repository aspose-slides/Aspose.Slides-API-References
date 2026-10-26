---
title: Save()
second_title: Aspose.Slides pro C++ API Reference
description: Uloží obrázek do souboru.
type: docs
weight: 40
url: /cs/aspose.slides/iimage/save/
---
## IImage::Save(System::String) metoda

Uloží obrázek do souboru.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Cesta k souboru, do kterého bude obrázek uložen. |

## IImage::Save(System::String, ImageFormat) metoda

Uloží obrázek do souboru ve specifikovaném formátu.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Cesta k souboru, do kterého bude obrázek uložen. |
| format | [ImageFormat](../../imageformat/) | Formát obrázku. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) metoda

Uloží obrázek do proudu ve specifikovaném formátu.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Proud, do kterého bude obrázek uložen. |
| format | [ImageFormat](../../imageformat/) | Formát obrázku. |

## IImage::Save(System::String, ImageFormat, int32_t) metoda

Uloží obrázek do souboru ve specifikovaném formátu a kvalitě.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Cesta k souboru, do kterého bude obrázek uložen. |
| format | [ImageFormat](../../imageformat/) | Formát obrázku. |
| quality | **int32_t** | Kvalita uloženého obrázku (0 až 100). 

 Tento parametr ovlivňuje ukládání pouze v [ImageFormat::Jpeg](../../imageformat/); u všech ostatních formátů je ignorován. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) metoda

Uloží obrázek do proudu ve specifikovaném formátu a kvalitě.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Proud, do kterého bude obrázek uložen. |
| format | [ImageFormat](../../imageformat/) | Formát obrázku. |
| quality | **int32_t** | Kvalita uloženého obrázku (0 až 100). 

 Tento parametr ovlivňuje ukládání pouze v [ImageFormat::Jpeg](../../imageformat/); u všech ostatních formátů je ignorován. |

## Viz také

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [IImage](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)