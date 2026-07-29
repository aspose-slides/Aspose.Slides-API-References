---
title: CreateMathematicalText()
second_title: Aspose.Slides för C++ API-referens
description: Skapa tomt matematiskt textelement
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() metod


Skapa tomt matematiskt textelement

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```


### Return Value

ny Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) metod


Skapa matematiskt textelement med det angivna värdet

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathSymbol | char16_t | enskild symbol att använda som textelementvärde |

### Return Value

ny Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) metod


Skapa tomt matematiskt textelement med det angivna värdet

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textelementvärde |

### Return Value

ny Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) metod


Skapa tomt matematiskt textelement med det angivna värdet och formateringsinställningar

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textelementvärde |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | textformatinställningar |

### Return Value

ny Mathematical Text

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathematicalText](../../imathematicaltext/)
* Klass [MathematicalTextFactory](../)
* Klass [String](../../../system/string/)
* Klass [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)