---
title: InsertFromHtml()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.
type: docs
weight: 157
url: /es/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlText | [System::String](../../../system/string/) | HTML a añadir. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Un URI del HTML especificado. Usado para resolver enlaces relativos. |

### Valor devuelto

Diapositivas añadidas.

## ISlideCollection::InsertFromHtml(int32_t, System::String) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlText | [System::String](../../../system/string/) | HTML a añadir. |

### Valor devuelto

Diapositivas añadidas

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que se usará como origen de un archivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Un URI del HTML especificado. Usado para resolver enlaces relativos. |

### Valor devuelto

Diapositivas añadidas.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que se usará como origen de un archivo HTML. |

### Valor devuelto

Diapositivas añadidas

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objeto Stream que se usará como origen de un archivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Un URI del HTML especificado. Usado para resolver enlaces relativos. |

### Valor devuelto

Diapositivas añadidas.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objeto Stream que se usará como origen de un archivo HTML. |

### Valor devuelto

Diapositivas añadidas

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlText | [System::String](../../../system/string/) | HTML a añadir. |
| useSlideWithIndexAsStart | **bool** | Esta bandera determina cómo iniciar la inserción: desde una diapositiva nueva o desde la diapositiva con el índice especificado. Si **true**, la inserción de datos comenzará en un espacio vacío de la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

### Valor devuelto

Diapositivas añadidas

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlText | [System::String](../../../system/string/) | HTML a añadir. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Un URI del HTML especificado. Usado para resolver enlaces relativos. |
| useSlideWithIndexAsStart | **bool** | Esta bandera determina cómo iniciar la inserción: desde una diapositiva nueva o desde la diapositiva con el índice especificado. Si **true**, la inserción de datos comenzará en un espacio vacío de la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

### Valor devuelto

Diapositivas añadidas.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objeto Stream que se usará como origen de un archivo HTML. |
| useSlideWithIndexAsStart | **bool** | Esta bandera determina cómo iniciar la inserción: desde una diapositiva nueva o desde la diapositiva con el índice especificado. Si **true**, la inserción de datos comenzará en un espacio vacío de la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

### Valor devuelto

Diapositivas añadidas

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) método


Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición para insertar. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objeto Stream que se usará como origen de un archivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Un URI del HTML especificado. Usado para resolver enlaces relativos. |
| useSlideWithIndexAsStart | **bool** | Esta bandera determina cómo iniciar la inserción: desde una diapositiva nueva o desde la diapositiva con el índice especificado. Si **true**, la inserción de datos comenzará en un espacio vacío de la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

### Valor devuelto

Diapositivas añadidas.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlide](../../islide/)
* Clase [String](../../../system/string/)
* Clase [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Clase [ISlideCollection](../)
* Clase [TextReader](../../../system.io/textreader/)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)