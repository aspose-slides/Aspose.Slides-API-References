---
title: CreateMathematicalText()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstelle leeres mathematisches Textelement
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() Methode

Erstelle leeres mathematisches Textelement

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Rückgabewert

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) Methode

Erstelle mathematisches Textelement mit dem angegebenen Wert

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char16_t | einzelnes Symbol, das als Textwert verwendet wird |

### Rückgabewert

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) Methode

Erstelle leeres mathematisches Textelement mit dem angegebenen Wert

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Textwert |

### Rückgabewert

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) Methode

Erstelle leeres mathematisches Textelement mit dem angegebenen Wert und Formatierungseigenschaften

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Textwert |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | Textformat-Einstellungen |

### Rückgabewert

new Mathematical Text

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathematicalText](../../imathematicaltext/)
* Klasse [IMathematicalTextFactory](../)
* Klasse [String](../../../system/string/)
* Klasse [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)