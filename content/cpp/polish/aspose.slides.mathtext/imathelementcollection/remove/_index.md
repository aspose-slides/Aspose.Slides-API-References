---
title: Remove()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) method


Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Obiekt, który ma zostać usunięty z kolekcji. |

### Wartość zwracana

true jeśli *item* został pomyślnie usunięty z kolekcji; w przeciwnym razie false. Ta metoda również zwraca false, jeśli *item* nie został znaleziony w pierwotnej kolekcji.
## Uwagi



Przykład: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathElementCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)