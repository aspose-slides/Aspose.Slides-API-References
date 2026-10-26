---
title: get_SeparatorCharacter()
second_title: Referência da API Aspose.Slides para C++
description: "Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'."
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() método


Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## Observações


Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Veja também

* Classe [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)