---
title: set_Character()
second_title: Referência da API Aspose.Slides para C++
description: "Caractere de Acento O valor deve estar dentro do intervalo (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Acento Circunflexo de Combinação (U+0302)"
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) método

Caractere de Acento O valor deve estar dentro do intervalo (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Acento Circunflexo de Combinação (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Observações

Exemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Veja Também

* Classe [IMathAccent](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)