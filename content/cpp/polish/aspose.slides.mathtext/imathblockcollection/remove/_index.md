---
title: Remove()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Usuwa pierwsze wystąpienie konkretnego obiektu z kolekcji/>.
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) metoda


Usuwa pierwsze wystąpienie konkretnego obiektu z kolekcji/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Obiekt do usunięcia z kolekcji. |

### Wartość zwrotna

true jeśli *item* został pomyślnie usunięty z kolekcji; w przeciwnym razie false. Ta metoda również zwraca false, jeśli *item* nie został znaleziony w pierwotnej kolekcji/>.

## Uwagi



Przykład: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathBlockCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)