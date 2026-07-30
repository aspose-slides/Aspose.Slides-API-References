---
title: CreateMathematicalText()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvořit prázdný matematický textový prvek
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() metoda


Vytvořit prázdný matematický textový prvek

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```


### Návratová hodnota

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) metoda


Vytvořit matematický textový prvek se zadanou hodnotou

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathSymbol | char16_t | jediný symbol použitý jako textová hodnota |

### Návratová hodnota

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) metoda


Vytvořit prázdný matematický textový prvek se zadanou hodnotou

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textová hodnota |

### Návratová hodnota

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) metoda


Vytvořit prázdný matematický textový prvek se zadanou hodnotou a vlastnostmi formátování

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textová hodnota |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | nastavení formátu textu |

### Návratová hodnota

new Mathematical Text

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathematicalText](../../imathematicaltext/)
* Class [MathematicalTextFactory](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)