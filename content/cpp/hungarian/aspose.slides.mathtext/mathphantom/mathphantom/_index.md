---
title: MathPhantom()
second_title: Aspose.Slides C++ API referencia
description: Új példányt hoz létre a MathPhantom osztályból a megadott alap matematikai elem használatával.
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) konstruktor


Új példányt hoz létre a(z) [MathPhantom](../) osztályból a megadott alap matematikai elemmel.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az a(z) [IMathElement](../../imathelement/) alapja, amelynek láthatóságát és elrendezését a fantom szabályozza. Ez az elem definiálja a tartalmat, amely elrejthető vagy megjeleníthető, miközben továbbra is befolyásolja a környező matematika geometriai igazítását. |
## Megjegyzések



A fantom elemet arra használják, hogy lefoglalják vagy elnyomják a base kifejezés vizuális helyét anélkül, hogy kötelezően megjelenítenék azt. Ennek megfelelője az OMML elem **<m:phant>**. 

Példa: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathPhantom](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)