---
title: ReadPresentation()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge una presentazione esistente da un array
type: docs
weight: 40
url: /it/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metodo

Legge una presentazione esistente da un array

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array da leggere |

### Valore di ritorno

Presentazione letta

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metodo

Legge una presentazione esistente da un array con opzioni di caricamento aggiuntive

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array da leggere |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opzioni di caricamento |

### Valore di ritorno

Presentazione letta

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metodo

Legge una presentazione esistente da uno stream

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di input da leggere |

### Valore di ritorno

Presentazione letta

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metodo

Legge una presentazione esistente da uno stream con opzioni di caricamento aggiuntive

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di input da leggere |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opzioni di caricamento |

### Valore di ritorno

Presentazione letta

## PresentationFactory::ReadPresentation(System::String) metodo

Legge una presentazione esistente da un file

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nome del file |

### Valore di ritorno

Presentazione letta

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metodo

Legge una presentazione esistente da un file con opzioni di caricamento aggiuntive

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nome del file |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opzioni di caricamento |

### Valore di ritorno

Presentazione letta

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPresentation](../../ipresentation/)
* Class [PresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)