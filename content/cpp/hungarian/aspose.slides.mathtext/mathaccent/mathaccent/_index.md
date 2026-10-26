---
title: MathAccent()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy matematikai ékezetet, amely egy megadott matematikai elemhez alkalmazza az alapértelmezett ékezet karakter értékét
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) konstruktor


Math accent-et hoz létre, amely egy megadott matematikai elemhez alkalmazza az alapértelmezett hangsúly karakter értékét

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | a hangsúly alkalmazásához használt matematikai elem |
## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) konstruktor


Math accent-et hoz létre, amely egy megadott matematikai elemre alkalmazódik

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | a hangsúly alkalmazásához használt matematikai elem |
| accentCharacter | char16_t | hangsúly karakter |
## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathAccent](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)