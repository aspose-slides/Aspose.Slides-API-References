---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Leitura bool. O valor padrão é false.
type: docs
weight: 105
url: /pt/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() método


Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Leitura **bool**. O valor padrão é **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Observações


Quando esta propriedade está definida como **true**, hyperlinks com chamadas JavaScript serão ignorados ao salvar.

Quando esta propriedade está definida como **false**, todos os hyperlinks serão salvos.

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Veja também

* Classe [SaveOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)