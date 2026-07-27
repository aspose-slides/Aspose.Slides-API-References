---
title: get_SkipJavaScriptLinks()
second_title: Referência da API Aspose.Slides para C++
description: Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação. Leitura bool. O valor padrão é false.
type: docs
weight: 105
url: /pt/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() método


Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação. Leitura **bool**. O valor padrão é **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Observações


Quando esta propriedade está definida como **true**, hiperlinks com chamadas JavaScript serão ignorados ao salvar.

Quando esta propriedade está definida como **false**, todos os hiperlinks serão salvos.

Exemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Ver também

* Classe [ISaveOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)