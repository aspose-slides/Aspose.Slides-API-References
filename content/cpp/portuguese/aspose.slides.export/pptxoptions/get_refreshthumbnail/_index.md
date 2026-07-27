---
title: get_RefreshThumbnail()
second_title: Referência da API Aspose.Slides para C++
description: Especifica se a miniatura da apresentação será atualizada. Leia bool. O valor padrão é true.
type: docs
weight: 53
url: /pt/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() método


Especifica se a miniatura da apresentação será atualizada. Leia **bool**. O valor padrão é **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Observações


Quando o valor da opção for **true**, a nova miniatura será gerada.

Quando o valor da opção for **false**, a miniatura atual será salva como está.

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Veja Também

* Classe [PptxOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)