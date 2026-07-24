---
title: MathematicalText()
second_title: Aspose.Slides für C++ API-Referenz
description: "Standardkonstruktor (erstellt String::Empty Wert)"
type: docs
weight: 40
url: /de/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() Konstruktor

Standardkonstruktor (erstellt String::Empty Wert)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Hinweise

Beispiel: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) Konstruktor

Erstelle [MathText](../../) mit einem einzelnen Symbol

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathSymbol | char16_t | einzelnes Symbol |
## Hinweise

Beispiel: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) Konstruktor

Erstelle [MathematicalText](../) aus Text

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Textwert |
## Hinweise

Beispiel: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) Konstruktor

Erstelle [MathematicalText](../) aus Text und Texteinstellungen

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Textwert |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | Texteinstellungen |
## Hinweise

Beispiel: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [MathematicalText](../)
* Klasse [String](../../../system/string/)
* Klasse [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)