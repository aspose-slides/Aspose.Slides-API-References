---
title: MathBox()
second_title: Aspose.Slides C++ API-referencia
description: Inicializálja a MathBox-ot a megadott elemmel argumentumként
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) konstruktor


Inicializálja a(z) [MathBox](../)-t a megadott elem argumentummal

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az az alapelem, amelyhez a doboz alkalmazva van. Lehet null. |
## Megjegyzések



Példa: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)