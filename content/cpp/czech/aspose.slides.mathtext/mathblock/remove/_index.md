---
title: Remove()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraňuje první výskyt konkrétního objektu ze sbírky.
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) method


Odstraňuje první výskyt konkrétního objektu ze sbírky.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Objekt, který má být odstraněn ze sbírky. |

### Návratová hodnota

true, pokud byl *item* úspěšně odstraněn ze sbírky; v opačném případě false. Tato metoda také vrací false, pokud *item* není nalezen v původní sbírce.

## Poznámky



Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathBlock](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)