---
title: get_OperatorEmulator()
second_title: Aspose.Slides pro C++ API Reference
description: "Emulátor operátoru. Když je nastaven na true, krabice a její obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako místo pro zalomení řádku a může být zarovnán k ostatním operátorům. Emulátory operátoru se často používají, když se jeden nebo více glyfů spojí do operátoru, například '=='. Výchozí hodnota: false"
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() metoda


Emulátor operátoru. Když je true, krabice a její obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako místo pro zalomení řádku a může být zarovnán k ostatním operátorům. Emulátory operátoru se často používají, když se jeden nebo více glyfů spojuje do operátoru, například '=='. Výchozí hodnota: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
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