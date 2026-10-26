---
title: LoadExternalFonts()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona pastas adicionais para buscar fontes.
type: docs
weight: 1
url: /pt/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) método

Adiciona pastas adicionais para localizar fontes.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Diretórios para ler fontes adicionais. |

## Observações

O exemplo a seguir mostra como carregar fontes personalizadas de .TTF 
```cpp
// O caminho para o diretório de documentos.
System::String dataDir = u"C:\\";

// pastas para buscar fontes
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Carregar as fontes do diretório de fontes personalizado
FontsLoader::LoadExternalFonts(folders);

// Fazer algum trabalho e renderizar a apresentação/slide
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Limpar o cache de fontes
FontsLoader::ClearCache();
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontsLoader](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)