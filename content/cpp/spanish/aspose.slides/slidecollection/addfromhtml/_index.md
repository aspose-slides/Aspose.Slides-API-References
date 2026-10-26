---
title: AddFromHtml()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea diapositivas a partir de texto HTML y las agrega al final de la colección.
type: docs
weight: 196
url: /es/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML a agregar. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Una URI del HTML especificado. Utilizada para resolver enlaces relativos. |

### Valor devuelto

Diapositivas añadidas.

## SlideCollection::AddFromHtml(System::String) método

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML a agregar. |

### Valor devuelto

Diapositivas añadidas

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que se usará como fuente de un archivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Una URI del HTML especificado. Utilizada para resolver enlaces relativos. |

### Valor devuelto

Diapositivas añadidas.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) método

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que se usará como fuente de un archivo HTML. |

### Valor devuelto

Diapositivas añadidas

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objeto Stream que se usará como fuente de un archivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | [System::String](../../../system/string/) | Una URI del HTML especificado. Utilizada para resolver enlaces relativos. |

### Valor devuelto

Diapositivas añadidas.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) método

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objeto Stream que se usará como fuente de un archivo HTML. |

### Valor devuelto

Diapositivas añadidas

## Observaciones

```cpp
// Crea una instancia de la clase Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Llama al método AddFromHtml y pasa el archivo HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Usa el método Save para guardar el archivo como documento PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlide](../../islide/)
* Clase [String](../../../system/string/)
* Clase [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Clase [SlideCollection](../)
* Clase [TextReader](../../../system.io/textreader/)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)