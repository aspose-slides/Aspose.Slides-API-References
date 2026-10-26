---
title: MathematicalText()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Konstruktor domyślny (tworzy wartość String::Empty)"
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() konstruktor

Konstruktor domyślny (utwórz wartość String::Empty)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Uwagi

Przykład:
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) konstruktor

Utwórz [MathText](../../) z pojedynczym symbolem

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathSymbol | char16_t | pojedynczy symbol |
## Uwagi

Przykład:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) konstruktor

Utwórz [MathematicalText](../) z tekstu

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | wartość tekstowa |
## Uwagi

Przykład:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) konstruktor

Utwórz [MathematicalText](../) z tekstu i ustawień formatu

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | wartość tekstowa |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | ustawienia formatu tekstu |
## Uwagi

Przykład:
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [MathematicalText](../)
* Klasa [String](../../../system/string/)
* Klasa [IPortionFormat](../../../aspose.slides/iportionformat/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)