---
title: set_RefreshThumbnail()
second_title: Referência da API Aspose.Slides para C++
description: Especifica se a miniatura da apresentação será atualizada. Escreva bool. O valor padrão é true.
type: docs
weight: 66
url: /pt/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) método

Especifica se a miniatura da apresentação será atualizada. Escreva **bool**. O valor padrão é **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
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

* Classe [IPptxOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)