---
title: MathAccent()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) konstruktor

Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego zastosować akcent |
## Uwagi

Przykład:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) konstruktor

Tworzy akcent matematyczny stosowany do określonego elementu matematycznego

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego zastosować akcent |
| accentCharacter | char16_t | znak akcentu |
## Uwagi

Przykład:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathAccent](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)