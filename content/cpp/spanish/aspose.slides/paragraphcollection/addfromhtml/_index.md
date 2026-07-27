---
title: AddFromHtml()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega texto de la cadena html especificada a la colección.
type: docs
weight: 157
url: /es/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) method

Agrega texto de la cadena html especificada a la colección.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto HTML. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Agrega texto de la cadena html especificada a la colección.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objeto de devolución de llamada del resolvedor que resuelve URIs y recupera los objetos referenciados. |
| uri | [System::String](../../../system/string/) | URI para agregar el documento HTML. Usado para resolver enlaces relativos. |

## Remarks

Especificar el resolvedor puede introducir potencialmente una vulnerabilidad. Úselo con precaución.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [ParagraphCollection](../)
* Clase [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)