---
title: AddFromHtml()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea diapositivas a partir de texto HTML y las agrega al final de la colección.
type: docs
weight: 144
url: /es/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML a agregar. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Una URI del HTML especificado. Usada para resolver enlaces relativos. |

### Valor devuelto

Diapositivas agregadas.

## ISlideCollection::AddFromHtml(System::String) method

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML a agregar. |

### Valor devuelto

Diapositivas agregadas

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que se usará como fuente de un archivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Una URI del HTML especificado. Usada para resolver enlaces relativos. |

### Valor devuelto

Diapositivas agregadas.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que se usará como fuente de un archivo HTML. |

### Valor devuelto

Diapositivas agregadas

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objeto Stream que se usará como fuente de un archivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Una URI del HTML especificado. Usada para resolver enlaces relativos. |

### Valor devuelto

Diapositivas agregadas.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objeto Stream que se usará como fuente de un archivo HTML. |

### Valor devuelto

Diapositivas agregadas

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