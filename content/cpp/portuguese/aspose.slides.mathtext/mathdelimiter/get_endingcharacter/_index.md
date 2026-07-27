---
title: get_EndingCharacter()
second_title: Referência da API Aspose.Slides para C++
description: "Delimiter Ending Character especifica o caractere delimitador de término, ou de fechamento. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O padrão: ')'."
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() método


Delimiter Ending Character especifica o caractere delimitador de término, ou de fechamento. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O padrão: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Observações


Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Veja Também

* Classe [MathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)