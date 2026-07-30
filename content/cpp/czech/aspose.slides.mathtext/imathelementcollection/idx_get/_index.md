---
title: idx_get()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací prvek na zadaném indexu. Pouze pro čtení IMathElement.
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) metoda

Vrací prvek na zadaném indexu. Pouze pro čtení [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the item to get |
## Poznámky


Příklad: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathElementCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)