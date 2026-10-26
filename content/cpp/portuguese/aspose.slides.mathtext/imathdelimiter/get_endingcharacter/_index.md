---
title: get_EndingCharacter()
second_title: Referência da API Aspose.Slides para C++
description: "O Caractere Final do Delimitador especifica o caractere delimitador final, ou de fechamento. Delimitadores matemáticos são caracteres de encadeamento, como parênteses, colchetes e chaves. O padrão: ')'."
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() method

O Caractere Final do Delimitador especifica o caractere delimitador final, ou de fechamento. Delimitadores matemáticos são caracteres de encadeamento, como parênteses, colchetes e chaves. O padrão: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Veja Também

* Classe [IMathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)