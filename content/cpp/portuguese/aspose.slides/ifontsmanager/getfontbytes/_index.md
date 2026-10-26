---
title: GetFontBytes()
second_title: Referência da API Aspose.Slides para C++
description: Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados.
type: docs
weight: 131
url: /pt/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) método

Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | O objeto de dados da fonte que contém as informações sobre a fonte [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | O estilo da fonte para o qual os dados devem ser recuperados [FontStyleType](../../fontstyletype/). |

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

## Veja Também

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)