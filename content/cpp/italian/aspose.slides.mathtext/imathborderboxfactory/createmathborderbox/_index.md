---
title: CreateMathBorderBox()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una border box matematica applicandola all'elemento
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) metodo

Crea una border box matematica applicandola all'elemento

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare la border box |

### Valore restituito

nuovo elemento border box

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) metodo

Crea una border box matematica applicandola all'elemento

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare la border box |
| hideTop | **bool** | Nascondi bordo superiore |
| hideBottom | **bool** | Nascondi bordo inferiore |
| hideLeft | **bool** | Nascondi bordo sinistro |
| hideRight | **bool** | Nascondi bordo destro |
| strikethroughHorizontal | **bool** | Border Box Strikethrough Horizontal |
| strikethroughVertical | **bool** | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | **bool** | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | **bool** | Border Box Strikethrough Top-Left to Bottom-Right |

### Valore restituito

nuovo elemento border box

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBorderBoxFactory](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)