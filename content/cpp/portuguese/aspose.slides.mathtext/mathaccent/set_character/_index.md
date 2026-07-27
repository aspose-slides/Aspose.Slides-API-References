---
title: set_Character()
second_title: Aspose.Slides para C++ Referência da API
description: "Caractere de acento O valor deve estar dentro do intervalo (U+0300\\u2013U+036F) ou(U+20D0\\u2013U+20EF) Valor padrão: Acento circunflexo combinável (U+0302)"
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) método


Caractere de acento O valor deve estar dentro do intervalo (U+0300\\u2013U+036F) ou(U+20D0\\u2013U+20EF) Valor padrão: Acento circunflexo combinável (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## Observações


Exemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Ver também

* Classe [MathAccent](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)