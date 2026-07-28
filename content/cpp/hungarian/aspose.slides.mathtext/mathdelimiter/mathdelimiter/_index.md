---
title: MathDelimiter()
second_title: Aspose.Slides C++ API referencia
description: Inicializálja a MathDelimiter-t a megadott elemmel, mint egyetlen alapargumentumot
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) konstruktor


Inicializálja a(z) [MathDelimiter](../)-t a megadott elemmel, mint egyetlen alapargumentumot

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az az alap elem, amelyre a határoló alkalmazásra kerül. Lehet null. |
## Megjegyzések



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)