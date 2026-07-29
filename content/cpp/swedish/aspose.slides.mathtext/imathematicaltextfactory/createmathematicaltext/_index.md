---
title: CreateMathematicalText()
second_title: Aspose.Slides för C++ API-referens
description: Skapa ett tomt matematiskt textelement
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() metod

Skapa ett tomt matematiskt textelement

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Returvärde

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) metod

Skapa ett matematiskt textelement med det angivna värdet

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char16_t | enstaka tecken att använda som textvärde |

### Returvärde

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) metod

Skapa ett tomt matematiskt textelement med det angivna värdet

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textvärde |

### Returvärde

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) metod

Skapa ett tomt matematiskt textelement med det angivna värdet och formateringsinställningar

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textvärde |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | textformatinställningar |

### Returvärde

new Mathematical Text

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathematicalText](../../imathematicaltext/)
* Klass [IMathematicalTextFactory](../)
* Klass [String](../../../system/string/)
* Klass [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)