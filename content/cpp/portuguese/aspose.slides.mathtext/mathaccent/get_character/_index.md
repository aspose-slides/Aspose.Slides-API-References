---
title: get_Character()
second_title: Referência da API Aspose.Slides para C++
description: "Caractere de acento O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Acento circunflexo de combinação (U+0302)"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() método

Caractere de Acento O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Acento Circunflexo de Combinação (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Observações


Exemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Ver Também

* Classe [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)