---
title: set_RefreshThumbnail()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica se a miniatura da apresentação será atualizada. Escreva bool. O valor padrão é true.
type: docs
weight: 66
url: /pt/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) método

Especifica se a miniatura da apresentação será atualizada. Escreva **bool**. O valor padrão é **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
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