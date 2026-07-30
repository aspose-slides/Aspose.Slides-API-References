---
title: Save()
second_title: Riferimento API Aspose.Slides per C++
description: Salva l'immagine su un file.
type: docs
weight: 40
url: /it/aspose.slides/iimage/save/
---
## IImage::Save(System::String) method

Salva l'immagine su un file.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Il percorso del file dove l'immagine verrà salvata. |

## IImage::Save(System::String, ImageFormat) method

Salva l'immagine su un file nel formato specificato.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Il percorso del file dove l'immagine verrà salvata. |
| format | [ImageFormat](../../imageformat/) | Il formato dell'immagine. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) method

Salva l'immagine su uno stream nel formato specificato.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Lo stream dove l'immagine verrà salvata. |
| format | [ImageFormat](../../imageformat/) | Il formato dell'immagine. |

## IImage::Save(System::String, ImageFormat, int32_t) method

Salva l'immagine su un file nel formato specificato e con la qualità indicata.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Il percorso del file dove l'immagine verrà salvata. |
| format | [ImageFormat](../../imageformat/) | Il formato dell'immagine. |
| quality | **int32_t** | La qualità dell'immagine salvata (0-100). 

Questo parametro influisce solo sul salvataggio in [ImageFormat::Jpeg](../../imageformat/); per tutti gli altri formati, viene ignorato. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) method

Salva l'immagine su uno stream nel formato specificato e con la qualità indicata.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Lo stream dove l'immagine verrà salvata. |
| format | [ImageFormat](../../imageformat/) | Il formato dell'immagine. |
| quality | **int32_t** | La qualità dell'immagine salvata (0-100). 

Questo parametro influisce solo sul salvataggio in [ImageFormat::Jpeg](../../imageformat/); per tutti gli altri formati, viene ignorato. |

## Vedi anche

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IImage](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)