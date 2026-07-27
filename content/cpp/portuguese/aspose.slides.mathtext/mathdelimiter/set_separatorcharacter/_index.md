---
title: set_SeparatorCharacter()
second_title: Referência da API Aspose.Slides para C++
description: "Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'."
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) método


Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Observações


Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Veja Também

* Classe [MathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)