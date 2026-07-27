---
title: get_SpellCheck()
second_title: Referência da API Aspose.Slides para C++
description: Obtém um valor que indica se a verificação ortográfica está habilitada para a parte de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é false.
type: docs
weight: 599
url: /pt/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() método

Obtém um valor que indica se a verificação ortográfica está habilitada para a parte de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definido como true, a verificação ortográfica é permitida. O valor padrão é **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Observações

O próximo exemplo demonstra como habilitar o sinalizador SpellCheck antes de salvar a apresentação: 
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

* Classe [IBasePortionFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)