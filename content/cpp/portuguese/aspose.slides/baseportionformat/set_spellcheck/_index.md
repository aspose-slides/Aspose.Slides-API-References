---
title: set_SpellCheck()
second_title: Referência da API Aspose.Slides para C++
description: Define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando essa propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é false.
type: docs
weight: 612
url: /pt/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) método

Define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando essa propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Observações

O próximo exemplo demonstra a habilitação da bandeira SpellCheck antes de salvar a apresentação: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Acesse a primeira porção de texto dentro da primeira forma no primeiro slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Habilite a verificação ortográfica para esta porção de texto
portion->get_PortionFormat()->set_SpellCheck(true);
// Salve a apresentação modificada
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Veja Também

* Classe [BasePortionFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)