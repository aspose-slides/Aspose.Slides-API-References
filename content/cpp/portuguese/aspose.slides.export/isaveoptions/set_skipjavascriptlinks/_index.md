---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica se deve ignorar hiperlinks com chamadas JavaScript ao salvar a apresentação. Escreva bool. O valor padrão é false.
type: docs
weight: 118
url: /pt/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) método


Especifica se deve ignorar hiperlinks com chamadas JavaScript ao salvar a apresentação. Escreva **bool**. O valor padrão é **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## Observações


Quando esta propriedade é definida como **true**, os hiperlinks com chamadas JavaScript serão ignorados ao salvar.

Quando esta propriedade é definida como **false**, todos os hiperlinks serão salvos.

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Ver também

* Classe [ISaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)