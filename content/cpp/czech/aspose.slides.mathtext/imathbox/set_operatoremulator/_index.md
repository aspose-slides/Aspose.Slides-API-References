---
title: set_OperatorEmulator()
second_title: Aspose.Slides pro C++ API Reference
description: "Operator Emulator. Když je true, krabice a její obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako místo pro zalomení řádku a může být zarovnán k ostatním operátorům. Operator Emulators se často používají, když se jeden nebo více glifů spojí do operátoru, například '=='. Výchozí hodnota: false"
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) metoda


Operator Emulator. Když je true, krabice a její obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako místo pro zalomení řádku a může být zarovnán k dalším operátorům. Operator Emulators se často používají, když se jeden nebo více glifů spojují do operátoru, například '=='. Výchozí hodnota: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Poznámky


Příklad: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Viz také

* Třída [IMathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)