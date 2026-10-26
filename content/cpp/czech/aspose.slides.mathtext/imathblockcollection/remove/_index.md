---
title: Remove()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odstraňuje první výskyt konkrétního objektu ze sbírky/>.
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) metoda

Odstraňuje první výskyt konkrétního objektu ze sbírky/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Objekt, který se má odebrat ze sbírky. |

### Návratová hodnota

true pokud *item* byl úspěšně odstraněn ze sbírky; jinak false. Tato metoda také vrací false, pokud *item* není nalezen v původní sbírce/>.

## Poznámky



Příklad: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [IMathBlockCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)