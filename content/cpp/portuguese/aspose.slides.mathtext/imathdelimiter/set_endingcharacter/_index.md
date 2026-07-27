---
title: set_EndingCharacter()
second_title: Referência da API Aspose.Slides for C++
description: "Delimiter Ending Character especifica o caractere delimitador de finalização ou fechamento. Delimitadores matemáticos são caracteres de encerramento como parênteses, colchetes e chaves. O padrão: ')'."
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) método

Delimiter Ending Character especifica o caractere delimitador de finalização ou fechamento. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O padrão: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Veja também

* Classe [IMathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)