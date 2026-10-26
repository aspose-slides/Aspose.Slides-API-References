---
title: GetFontBytes()
second_title: Referência da API Aspose.Slides para C++
description: Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados.
type: docs
weight: 131
url: /pt/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) method


Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | O objeto de dados da fonte que contém as informações sobre a fonte [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | O estilo da fonte para o qual os dados devem ser recuperados [FontStyleType](../../fontstyletype/). |

### Valor de Retorno

Um array de bytes contendo os dados da fonte para o estilo de fonte especificado. Se os dados da fonte ou o estilo não forem encontrados, retorna null.
## Observações




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Ver Também

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)