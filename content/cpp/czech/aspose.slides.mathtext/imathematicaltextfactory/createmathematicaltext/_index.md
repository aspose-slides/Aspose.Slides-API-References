---
title: CreateMathematicalText()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří prázdný prvek matematického textu
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() method


Vytvořit prázdný prvek matematického textu

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```


### Návratová hodnota

nový Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) method


Vytvořit prvek matematického textu se zadanou hodnotou

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathSymbol | char16_t | jediný symbol použitý jako textová hodnota |

### Návratová hodnota

nový Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) method


Vytvořit prázdný prvek matematického textu se zadanou hodnotou

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textová hodnota |

### Návratová hodnota

nový Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) method


Vytvořit prázdný prvek matematického textu se zadanou hodnotou a vlastnostmi formátování

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textová hodnota |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | nastavení formátu textu |

### Návratová hodnota

nový Mathematical Text

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathematicalText](../../imathematicaltext/)
* Třída [IMathematicalTextFactory](../)
* Třída [String](../../../system/string/)
* Třída [IPortionFormat](../../../aspose.slides/iportionformat/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)