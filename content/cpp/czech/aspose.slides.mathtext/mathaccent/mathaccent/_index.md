---
title: MathAccent()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou akcentového znaku
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) konstruktor


Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou akcentového znaku

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje akcent |
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) konstruktor


Vytvoří matematický akcent aplikovaný na zadaný matematický prvek

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje akcent |
| accentCharacter | char16_t | znak akcentu |
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathElement](../../imathelement/)
* třída [MathAccent](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)