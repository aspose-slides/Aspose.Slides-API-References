---
title: GetFontEmbeddingLevel()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina el nivel de incrustación de una fuente a partir del arreglo de bytes proporcionado y del nombre de la fuente.
type: docs
weight: 144
url: /es/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) method


Determina el nivel de incrustación de una fuente a partir del arreglo de bytes proporcionado y del nombre de la fuente.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El arreglo de bytes que contiene los datos de la fuente. |
| fontName | [System::String](../../../system/string/) | El nombre de la fuente. |

### Valor de retorno

El nivel de incrustación de la fuente especificada.
## Observaciones




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Recupera todas las fuentes usadas en la presentación
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Obtiene el arreglo de bytes que representa el estilo regular de la primera fuente en la presentación
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determina el nivel de incrustación de la fuente
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Véase también

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [FontsManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)