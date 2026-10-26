---
title: set_OperatorEmulator()
second_title: Aspose.Slides pro C++ API referenci
description: "Emulátor operátoru. Když je nastaven na true, krabice a její obsah se chovají jako jeden operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako místo pro zalomení řádku a může být zarovnán k dalším operátorům. Emulátory operátorů se často používají, když se jeden nebo více glyfů spojí a vytvoří operátor, například '=='. Výchozí hodnota: false"
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) metoda

Emulátor operátoru. Když je hodnota true, krabice a její obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako místo pro zalomení řádku a může být zarovnán k dalším operátorům. Emulátory operátorů se často používají, když se jeden nebo více glyfů spojuje a vytvoří operátor, například '=='. Výchozí hodnota: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Poznámky

Příklad:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Viz také

* Třída [MathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)