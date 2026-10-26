---
title: AddImage()
second_title: Aspose.Slides per C++ - Riferimento API
description: Aggiungi un'immagine a una presentazione.
type: docs
weight: 14
url: /it/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) method


Aggiungi un'immagine a una presentazione.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Immagine da aggiungere. |

### Valore restituito

Immagine aggiunta.
## Note


Questo metodo converte i metafili WMF/EMF in immagini PNG raster prima di inserirli in una presentazione.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) method


Aggiunge un'immagine da un flusso di memoria.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Flusso di memoria. |

### Valore restituito

Immagine aggiunta.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) method


Aggiungi un'immagine a una presentazione da un flusso.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso da cui aggiungere l'immagine. |

### Valore restituito

Immagine aggiunta.
## Note


Questo metodo può aggiungere metafili WMF/EMF a una presentazione senza convertirli in immagini PNG raster.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method


Crea e aggiunge un'immagine a una presentazione da un flusso.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso da cui aggiungere il file immagine. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Il comportamento che verrà applicato al flusso. |

### Valore restituito

Aggiunto [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) method


Aggiunge un'immagine a una presentazione da un buffer specificato.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Valore restituito

Immagine aggiunta.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) method


Aggiunge una copia di un'immagine da un'altra presentazione.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Immagine sorgente. |

### Valore restituito

Immagine aggiunta.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) method


Aggiungi un'immagine a una presentazione da un oggetto SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Oggetto immagine SVG [ISvgImage](../../isvgimage/) |

### Valore restituito

Immagine aggiunta.

## Vedi anche

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)