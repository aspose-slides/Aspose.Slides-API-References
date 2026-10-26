---
title: ReadPresentation()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge una presentazione esistente da un array
type: docs
weight: 27
url: /it/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metodo

Legge una presentazione esistente da un array

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array da leggere |

### Valore di ritorno

Presentazione letta

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metodo

Legge una presentazione esistente da un array con opzioni di caricamento aggiuntive

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array da leggere |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opzioni di caricamento |

### Valore di ritorno

Presentazione letta

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metodo

Legge una presentazione esistente da uno stream

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di input da leggere |

### Valore di ritorno

Presentazione letta

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metodo

Legge una presentazione esistente da uno stream con opzioni di caricamento aggiuntive

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di input da leggere |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opzioni di caricamento |

### Valore di ritorno

Presentazione letta

## IPresentationFactory::ReadPresentation(System::String) metodo

Legge una presentazione esistente da un file

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nome file |

### Valore di ritorno

Presentazione letta

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metodo

Legge una presentazione esistente da un file con opzioni di caricamento aggiuntive

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nome file |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opzioni di caricamento |

### Valore di ritorno

Presentazione letta

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IPresentation](../../ipresentation/)
* Classe [IPresentationFactory](../)
* Classe [ILoadOptions](../../iloadoptions/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)