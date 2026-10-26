---
title: get_OperatorEmulator()
second_title: Aspose.Slides pro C++ API Reference
description: "Operator Emulator. Když je nastaven na true, box a jeho obsah se chovají jako jeden operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako místo pro zalomení řádku a může být zarovnán k dalším operátorům. Operator Emulátory se často používají, když se jeden nebo více glyfů spojí a vytvoří operátor, například '=='. Výchozí hodnota: false"
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() metoda


Operator Emulator. Když je nastaveno na true, box a jeho obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako místo pro zalomení řádku a může být zarovnán k dalším operátorům. Operator Emulators se často používají, když se jeden nebo více glyfů spojují a tvoří operátor, jako je '=='. Výchozí hodnota: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
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