---
title: CreateMathematicalText()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Utwórz pusty element tekstu matematycznego
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() metoda

Utwórz pusty element Mathematical Text

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Wartość zwracana

nowy Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) metoda

Utwórz element Mathematical Text o określonej wartości

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathSymbol | char16_t | pojedynczy znak używany jako wartość tekstowa |

### Wartość zwracana

nowy Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) metoda

Utwórz pusty element Mathematical Text o określonej wartości

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | wartość tekstowa |

### Wartość zwracana

nowy Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) metoda

Utwórz pusty element Mathematical Text o określonej wartości i właściwościach formatowania

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | wartość tekstowa |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | ustawienia formatu tekstu |

### Wartość zwracana

nowy Mathematical Text

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathematicalText](../../imathematicaltext/)
* Klasa [IMathematicalTextFactory](../)
* Klasa [String](../../../system/string/)
* Klasa [IPortionFormat](../../../aspose.slides/iportionformat/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)