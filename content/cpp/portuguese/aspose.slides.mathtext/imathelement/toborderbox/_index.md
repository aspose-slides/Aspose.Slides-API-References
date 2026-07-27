---
title: ToBorderBox()
second_title: Referência da API Aspose.Slides para C++
description: Coloca este elemento dentro de um border-box
type: docs
weight: 261
url: /pt/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() método


Places this element in a border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Valor de Retorno

Border-box with this element placed inside
## Observações



Exemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) método


Places this element in a border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | Hide Top Edge |
| hideBottom | **bool** | Hide Bottom Edge |
| hideLeft | **bool** | Hide Left Edge |
| hideRight | **bool** | Hide Right Edge |
| strikethroughHorizontal | **bool** | Border Box Strikethrough Horizontal |
| strikethroughVertical | **bool** | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | **bool** | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | **bool** | Border Box Strikethrough Top-Left to Bottom-Right |

### Valor de Retorno

Border-box with this element placed inside
## Observações



Exemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [IMathElement](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)