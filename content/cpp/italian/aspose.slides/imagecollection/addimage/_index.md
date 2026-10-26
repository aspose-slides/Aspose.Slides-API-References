---
title: AddImage()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una copia di un'immagine da un'altra presentazione.
type: docs
weight: 53
url: /it/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metodo


Aggiunge una copia di un'immagine da un'altra presentazione.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### Argumenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Immagine di origine. |

### Valore di ritorno

Immagine aggiunta.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) metodo


Aggiunge un'immagine a una presentazione.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### Argumenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Immagine da aggiungere. |

### Valore di ritorno

Immagine aggiunta.

## Osservazioni


Questo metodo converte i metafili WMF/EMF in immagini PNG raster prima di inserirli in una presentazione.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metodo


Aggiunge un'immagine a una presentazione da un flusso.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### Argumenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Flusso da cui aggiungere l'immagine. |

### Valore di ritorno

Immagine aggiunta.

## Osservazioni


Questo metodo può aggiungere metafili WMF/EMF a una presentazione senza convertirli in immagini PNG raster.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metodo


Aggiunge un'immagine a una presentazione da un flusso.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso da cui aggiungere l'immagine. |

### Valore di ritorno

Immagine aggiunta.

## Osservazioni


Questo metodo può aggiungere metafili WMF/EMF a una presentazione senza convertirli in immagini PNG raster.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metodo


Crea e aggiunge un'immagine a una presentazione da un flusso.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso da cui aggiungere il file immagine. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Il comportamento che sarà applicato al flusso. |

### Valore di ritorno

Aggiunto [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metodo


Aggiunge un'immagine a una presentazione da un buffer specificato.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### Argumenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Valore di ritorno

Immagine aggiunta.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metodo


Aggiunge un'immagine a una presentazione da un oggetto Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### Argumenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Oggetto immagine Svg [ISvgImage](../../isvgimage/) |

### Valore di ritorno

Immagine aggiunta.

## Vedi anche

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)