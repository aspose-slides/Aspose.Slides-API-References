---
title: MathPhantom()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert eine neue Instanz der MathPhantom-Klasse mit dem angegebenen Basismathelement.
type: docs
weight: 144
url: /de/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) Konstruktor


Initialisiert eine neue Instanz der [MathPhantom](../) Klasse mit dem angegebenen Basismathelement.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Basiselement [IMathElement](../../imathelement/), dessen Sichtbarkeit und Layout vom Phantom gesteuert werden. Dieses Element definiert den Inhalt, der ausgeblendet oder eingeblendet werden kann, während es dennoch die geometrische Ausrichtung der umgebenden Mathematik beeinflusst. |
## Bemerkungen



Das Phantom-Element wird verwendet, um den visuellen Raum seines Basisausdrucks zu reservieren oder zu unterdrücken, ohne ihn unbedingt anzuzeigen. Es entspricht dem OMML-Element **<m:phant>**. 

Beispiel: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathPhantom](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)