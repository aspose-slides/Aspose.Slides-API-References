---
title: CreateMathematicalText()
second_title: Aspose.Slides für C++ API-Referenz
description: Leeres mathematisches Textelement erstellen
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() Methode

Leeres mathematisches Textelement erstellen

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```

### Rückgabewert

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) Methode

Mathematisches Textelement mit dem angegebenen Wert erstellen

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathSymbol | char16_t | einzelnes Symbol, das als Textwert verwendet wird |

### Rückgabewert

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) Methode

Leeres mathematisches Textelement mit dem angegebenen Wert erstellen

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Textwert |

### Rückgabewert

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) Methode

Leeres mathematisches Textelement mit dem angegebenen Wert und Formatierungseigenschaften erstellen

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Textwert |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | Texteinstellungen |

### Rückgabewert

new Mathematical Text

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathematicalText](../../imathematicaltext/)
* Klasse [MathematicalTextFactory](../)
* Klasse [String](../../../system/string/)
* Klasse [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)