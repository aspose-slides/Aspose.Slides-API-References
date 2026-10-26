---
title: MathematicalText()
second_title: Aspose.Slides voor C++ API-referentie
description: "Standaardconstructor (maak String::Empty waarde)"
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() constructor

Standaardconstructor (maak String::Empty waarde)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Opmerkingen

Voorbeeld: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) constructor

Maak [MathText](../../) met één symbool

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathSymbol | char16_t | enkel symbool |
## Opmerkingen

Voorbeeld: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) constructor

Maak [MathematicalText](../) uit tekst

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | tekstwaarde |
## Opmerkingen

Voorbeeld: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) constructor

Maak [MathematicalText](../) uit tekst en opmaakinstellingen

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | tekstwaarde |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | tekstopmaakinstellingen |
## Opmerkingen

Voorbeeld: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [MathematicalText](../)
* Klasse [String](../../../system/string/)
* Klasse [IPortionFormat](../../../aspose.slides/iportionformat/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)