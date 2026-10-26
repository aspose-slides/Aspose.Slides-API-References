---
title: set_BeginningCharacter()
second_title: Referência da API Aspose.Slides para C++
description: "Delimiter Beginning Character especifica o caractere delimitador de início, ou de abertura. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O valor padrão: '('."
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) método

Delimiter Beginning Character especifica o caractere delimitador de início, ou de abertura. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O valor padrão: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Ver também

* Classe [IMathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)