---
title: get_BeginningCharacter()
second_title: Aspose.Slides para C++ Referência da API
description: "O Caractere Inicial do Delimitador especifica o caractere delimitador de início, ou de abertura. Delimitadores matemáticos são caracteres que delimitam, como parênteses, colchetes e chaves. O padrão: '('."
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() método


O Caractere Inicial do Delimitador especifica o caractere delimitador de início ou abertura. Delimitadores matemáticos são caracteres de fechamento, como parênteses, colchetes e chaves. O padrão: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Observações


Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Ver também

* Classe [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)