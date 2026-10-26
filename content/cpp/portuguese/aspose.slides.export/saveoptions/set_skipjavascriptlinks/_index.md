---
title: set_SkipJavaScriptLinks()
second_title: Referência da API Aspose.Slides para C++
description: Especifica se deve ignorar hiperlinks com chamadas JavaScript ao salvar a apresentação. Escreva bool. O valor padrão é false.
type: docs
weight: 118
url: /pt/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) método

Especifica se deve ignorar hiperlinks com chamadas JavaScript ao salvar a apresentação. Escreva **bool**. O valor padrão é **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Observações

Quando esta propriedade é definida como **true**, hiperlinks com chamadas JavaScript serão ignorados ao salvar.

Quando esta propriedade é definida como **false**, todos os hiperlinks serão salvos.

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Ver Também

* Classe [SaveOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)