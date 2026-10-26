---
title: MathBorderBox()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea l'elemento MathBorderBox con bordo rettangolare
type: docs
weight: 222
url: /it/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) costruttore


Crea l'elemento [MathBorderBox](../) con bordo rettangolare

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento base a cui viene applicato il riquadro del bordo. Può essere nullo. |
## Osservazioni



Esempio: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) costruttore


Crea l'elemento [MathBorderBox](../)

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento base a cui viene applicato il riquadro del bordo. |
| hideTop | **bool** | Nascondi il bordo superiore |
| hideBottom | **bool** | Nascondi il bordo inferiore |
| hideLeft | **bool** | Nascondi il bordo sinistro |
| hideRight | **bool** | Nascondi il bordo destro |
| strikethroughHorizontal | **bool** | Barra orizzontale |
| strikethroughVertical | **bool** | Barra verticale |
| strikethroughBottomLeftToTopRight | **bool** | Barra dal basso a sinistra all'alto a destra |
| strikethroughTopLeftToBottomRight | **bool** | Barra dall'alto a sinistra al basso a destra |
## Osservazioni



Esempio: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)