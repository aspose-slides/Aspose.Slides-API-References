---
title: get_Character()
second_title: Referência da API Aspose.Slides para C++
description: "Caractere de Acento O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou(U+20D0\\u2013U+20EF) Valor padrão: Acento Circunflexo Combinante (U+0302)"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() método

Caractere de Acento O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou(U+20D0\\u2013U+20EF) Valor padrão: Acento Circunflexo Combinante (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
```

## Observações

Exemplo:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Ver também

* Classe [IMathAccent](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)