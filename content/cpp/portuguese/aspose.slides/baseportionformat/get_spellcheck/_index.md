---
title: get_SpellCheck()
second_title: Referência da API Aspose.Slides para C++
description: Obtém um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é false.
type: docs
weight: 599
url: /pt/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() method


Obtém um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando essa propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Observações


O próximo exemplo demonstra a ativação da bandeira SpellCheck antes de salvar a apresentação: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Ver também

* Classe [BasePortionFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)