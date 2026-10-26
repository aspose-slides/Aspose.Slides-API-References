---
title: MathBar()
second_title: Aspose.Slides C++ API referencia
description: Inicializálja a MathBar-t felülvonallal (Felső pozíció)
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) konstruktor

Inicializálja a(z) [MathBar](../)-t felülvonallal (Felső pozíció)

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az az alapelem, amelyhez a vonalat hozzáadják |
## Megjegyzések



Példa: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) konstruktor

Inicializálja a(z) [MathBar](../)-t megadott pozícióval

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az az alapelem, amelyhez a vonalat hozzáadják |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | A vonal pozíciója. |
## Megjegyzések



Példa: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## Lásd még

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBar](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)