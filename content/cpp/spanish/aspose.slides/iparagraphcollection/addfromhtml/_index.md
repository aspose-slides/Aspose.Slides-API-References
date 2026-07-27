---
title: AddFromHtml()
second_title: Referencia de API de Aspose.Slides para C++
description: Añade texto desde la cadena html especificada a la colección.
type: docs
weight: 92
url: /es/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) método

Añade texto desde la cadena html especificada a la colección.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | texto HTML. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método

Añade texto desde la cadena html especificada a la colección.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | texto HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objeto de devolución de llamada del resolvedor que resuelve URIs y recupera los objetos referenciados. |
| uri | [System::String](../../../system/string/) | URI para agregar el documento HTML. Utilizado para resolver enlaces relativos. |
## Observaciones

Especificar un resolvedor puede introducir potencialmente una vulnerabilidad. Úselo con precaución.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [IParagraphCollection](../)
* Clase [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)