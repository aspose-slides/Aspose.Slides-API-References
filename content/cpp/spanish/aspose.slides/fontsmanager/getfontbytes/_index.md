---
title: GetFontBytes()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la matriz de bytes que representa los datos de fuente para un estilo de fuente y datos de fuente especificados.
type: docs
weight: 131
url: /es/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) método


Obtiene la matriz de bytes que representa los datos de fuente para un estilo de fuente y datos de fuente especificados.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | El objeto de datos de fuente que contiene la información sobre la fuente [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | El estilo de la fuente para el cual se deben obtener los datos [FontStyleType](../../fontstyletype/). |

### Valor de retorno

Una matriz de bytes que contiene los datos de fuente para el estilo de fuente especificado. Si los datos de fuente o el estilo no se encuentran, devuelve null.
## Observaciones




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Ver también

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)