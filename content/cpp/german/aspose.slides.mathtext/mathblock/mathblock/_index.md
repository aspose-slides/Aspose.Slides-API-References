---
title: MathBlock()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert eine neue Instanz der MathBlock-Klasse.
type: docs
weight: 66
url: /de/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() Konstruktor

Initialisiert eine neue Instanz der [MathBlock](../) Klasse.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Hinweise

Beispiel:
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) Konstruktor

Erstellt einen neuen mathematischen Block und fügt das angegebene Element darin ein

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das mathematische Element, das in den Block eingefügt werden soll |
## Hinweise

Beispiel:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) Konstruktor

Erstellt einen neuen mathematischen Block und fügt die angegebenen Elemente darin ein

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Mathematische Elemente, die in den Block eingefügt werden sollen |
## Hinweise

Beispiel:
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [MathBlock](../)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)