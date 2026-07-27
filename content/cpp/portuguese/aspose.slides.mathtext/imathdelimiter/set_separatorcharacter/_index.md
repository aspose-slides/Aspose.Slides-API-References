---
title: set_SeparatorCharacter()
second_title: Referência da API Aspose.Slides para C++
description: "Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'."
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) método

Delimiter Separator Character especifica o caractere que separa os argumentos no objeto delimitador. O padrão: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Veja Também

* Classe [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)