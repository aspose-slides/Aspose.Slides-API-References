---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den första förekomsten av ett specifikt objekt från samlingen.
type: docs
weight: 92
url: /sv/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) metod

Tar bort den första förekomsten av ett specifikt objekt från samlingen.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Objektet som ska tas bort från samlingen. |

### Returvärde

true om *item*  framgångsrikt togs bort från samlingen; annars false. Denna metod returnerar också false om *item*  inte finns i den ursprungliga samlingen.

## Anmärkningar

Exempel: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathElementCollection](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)