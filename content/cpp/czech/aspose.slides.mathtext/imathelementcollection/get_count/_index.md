---
title: get_Count()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací počet prvků, které jsou ve skutečnosti obsaženy v kolekci. Pouze pro čtení int32_t.
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() metoda

Vrací počet prvků, které jsou ve skutečnosti obsaženy v kolekci. Pouze pro čtení **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## Poznámky


Příklad:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## Viz také

* Třída [IMathElementCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)