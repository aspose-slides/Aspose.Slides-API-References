---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides para C++ Referência da API
description: Determina o nível de incorporação de uma fonte a partir do array de bytes fornecido e do nome da fonte.
type: docs
weight: 144
url: /pt/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) method


Determina o nível de incorporação de uma fonte a partir do array de bytes fornecido e do nome da fonte.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes que contém os dados da fonte. |
| fontName | [System::String](../../../system/string/) | O nome da fonte. |

### Valor de Retorno

O nível de incorporação da fonte especificada.
## Observações




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Recupera todas as fontes usadas na apresentação
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Obtém o array de bytes que representa o estilo regular da primeira fonte na apresentação
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determina o nível de incorporação da fonte
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Veja Também

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)