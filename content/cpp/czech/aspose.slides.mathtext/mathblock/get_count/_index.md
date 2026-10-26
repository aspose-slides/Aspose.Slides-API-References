---
title: get_Count()
second_title: Aspose.Slides pro C++ API Referenci
description: Vrací počet podřízených matematických prvků, které jsou ve skutečnosti obsaženy v kolekci. Pouze pro čtení int32_t.
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() metoda


Vrací počet podřízených matematických prvků, které jsou ve skutečnosti obsaženy v kolekci. Pouze pro čtení **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## Poznámky


Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## Viz také

* Třída [MathBlock](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)