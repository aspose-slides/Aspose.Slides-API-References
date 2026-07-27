---
title: set_EndingCharacter()
second_title: Referência da API Aspose.Slides para C++
description: "Delimiter Ending Character especifica o caractere delimitador final, ou de fechamento. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O padrão: ')'."
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) método

Delimiter Ending Character especifica o caractere delimitador final, ou de fechamento. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O padrão: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Ver Também

* Classe [MathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)