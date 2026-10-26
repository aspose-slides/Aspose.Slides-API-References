---
title: MathematicalText()
second_title: Aspose.Slides för C++ API-referens
description: "Standardkonstruktor (skapa String::Empty Value)"
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() konstruktor


Standardkonstruktor (skapa String::Empty Value)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Anmärkningar


Exempel: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) konstruktor


Skapa [MathText](../../) med en enda symbol

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| mathSymbol | char16_t | enkel symbol |
## Anmärkningar



Exempel: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) konstruktor


Skapa [MathematicalText](../) från text

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textvärde |
## Anmärkningar



Exempel: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) konstruktor


Skapa [MathematicalText](../) från text och formatinställningar

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textvärde |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | inställningar för textformat |
## Anmärkningar



Exempel: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [MathematicalText](../)
* Klass [String](../../../system/string/)
* Klass [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)