---
title: get_RefreshThumbnail()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica se a miniatura da apresentação será atualizada. Leitura bool. Valor padrão é true.
type: docs
weight: 53
url: /pt/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() método


Especifica se a miniatura da apresentação será atualizada. Leitura **bool**. O valor padrão é **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
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
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)