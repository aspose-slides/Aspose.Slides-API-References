---
title: Remove()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Odstraní první výskyt specifického objektu ze sbírky.
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) metoda


Odstraňuje první výskyt specifického objektu ze sbírky.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Objekt, který má být odebrán ze sbírky. |

### Návratová hodnota

true pokud je *item* úspěšně odebrán ze sbírky; jinak false. Tato metoda také vrací false, pokud *item* není nalezen v původní sbírce.
## Poznámky



Příklad: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathElementCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)