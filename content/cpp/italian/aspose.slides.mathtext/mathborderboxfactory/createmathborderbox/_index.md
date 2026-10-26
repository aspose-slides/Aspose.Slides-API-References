---
title: CreateMathBorderBox()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un riquadro di bordo matematico applicandolo all'elemento
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) metodo

Crea un riquadro di bordo matematico applicandolo all'elemento

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare il riquadro di bordo |

### Valore di ritorno

nuovo elemento del riquadro di bordo

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) metodo

Crea un riquadro di bordo matematico applicandolo all'elemento

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare il riquadro di bordo |
| hideTop | **bool** | Nascondi bordo superiore |
| hideBottom | **bool** | Nascondi bordo inferiore |
| hideLeft | **bool** | Nascondi bordo sinistro |
| hideRight | **bool** | Nascondi bordo destro |
| strikethroughHorizontal | **bool** | Barra orizzontale del riquadro di bordo |
| strikethroughVertical | **bool** | Barra verticale del riquadro di bordo |
| strikethroughBottomLeftToTopRight | **bool** | Barra diagonale dal basso sinistro al alto destro del riquadro di bordo |
| strikethroughTopLeftToBottomRight | **bool** | Barra diagonale dall'alto sinistro al basso destro del riquadro di bordo |

### Valore di ritorno

nuovo elemento del riquadro di bordo

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)