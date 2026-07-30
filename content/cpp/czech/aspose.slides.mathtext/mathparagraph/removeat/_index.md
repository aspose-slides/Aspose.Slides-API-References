---
title: RemoveAt()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odstraní položku na zadaném indexu kolekce.
type: docs
weight: 157
url: /cs/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) metoda


Odstraní položku na zadaném indexu kolekce.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index položky, která má být odstraněna. |
## Poznámky



Příklad: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## Viz také

* Třída [MathParagraph](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)