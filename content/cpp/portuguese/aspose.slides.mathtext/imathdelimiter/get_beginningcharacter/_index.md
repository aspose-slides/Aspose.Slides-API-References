---
title: get_BeginningCharacter()
second_title: "Referência da API Aspose.Slides para C++"
description: "Delimiter Beginning Character especifica o caractere delimitador inicial, ou de abertura. Delimitadores matemáticos são caracteres de fechamento, como parênteses, colchetes e chaves. O valor padrão: '('."
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() método


Delimiter Beginning Character especifica o caractere delimitador inicial, ou de abertura. Delimitadores matemáticos são caracteres de fechamento, como parênteses, colchetes e chaves. O valor padrão: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Observações


Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Ver também

* Classe [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)