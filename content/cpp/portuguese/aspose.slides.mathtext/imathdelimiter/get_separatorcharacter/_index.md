---
title: get_SeparatorCharacter()
second_title: Aspose.Slides para C++ Referência da API
description: "Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'."
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() método


Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Observações


Exemplo:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Ver também

* Classe [IMathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)