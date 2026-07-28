---
title: Remove()
second_title: Aspose.Slides dla C++ API Reference
description: Usuwa pierwsze wystąpienie określonego obiektu z kolekcji/>.
type: docs
weight: 105
url: /pl/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) metoda


Usuwa pierwsze wystąpienie określonego obiektu z kolekcji/>.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Obiekt do usunięcia z kolekcji. |

### Wartość zwracana

true jeśli *mathBlock* został pomyślnie usunięty z kolekcji; w przeciwnym razie false. Ta metoda również zwraca false, jeśli *mathBlock* nie został znaleziony w pierwotnej kolekcji/>.
## Uwagi



Przykład: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [MathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)