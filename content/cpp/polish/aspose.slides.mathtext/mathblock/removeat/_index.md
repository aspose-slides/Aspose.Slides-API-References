---
title: RemoveAt()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Usuwa element pod wskazanym indeksem w kolekcji.
type: docs
weight: 170
url: /pl/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) metoda


Usuwa element pod wskazanym indeksem w kolekcji.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Zero-bazowy indeks elementu do usunięcia. |
## Uwagi



Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Zobacz także

* Klasa [MathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)