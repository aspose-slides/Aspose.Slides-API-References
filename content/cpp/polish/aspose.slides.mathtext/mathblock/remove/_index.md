---
title: Remove()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) metoda


Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Obiekt do usunięcia z kolekcji. |

### Wartość zwracana

true jeśli *item* został pomyślnie usunięty z kolekcji; w przeciwnym razie false. Ta metoda również zwraca false, jeśli *item* nie zostanie znaleziony w pierwotnej kolekcji.
## Uwaga



Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)