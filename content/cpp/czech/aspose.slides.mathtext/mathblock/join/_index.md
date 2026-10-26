---
title: Join()
second_title: Aspose.Slides pro C++ API Reference
description: Spojuje matematický prvek s tímto matematickým blokem
type: docs
weight: 183
url: /cs/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) metoda

Spojuje matematický prvek s tímto matematickým blokem

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Prvek, který má být spojen |

### Návratová hodnota

Aktuální instance [IMathBlock](../../imathblock/)
## Poznámky



Příklad:
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) metoda

Spojuje matematický text s tímto matematickým blokem

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Matematický text, který má být spojen |

### Návratová hodnota

Nový [IMathBlock](../../imathblock/) obsahující tuto instanci a zadaný argument
## Poznámky



Příklad:
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathBlock](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)