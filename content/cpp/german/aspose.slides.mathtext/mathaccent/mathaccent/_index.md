---
title: MathAccent()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathe-Element mit dem Standardwert für das Akzentzeichen angewendet wird
type: docs
weight: 40
url: /de/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) Konstruktor


Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathe-Element angewendet wird, mit dem Standardwert für das Akzentzeichen

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ein Mathe-Element, dem das Akzent angewendet wird |
## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) Konstruktor


Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathe-Element angewendet wird

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathe-Element, dem das Akzent angewendet wird |
| accentCharacter | char16_t | Akzentzeichen |
## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)