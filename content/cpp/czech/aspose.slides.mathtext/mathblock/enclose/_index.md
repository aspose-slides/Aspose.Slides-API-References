---
title: Enclose()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Obaluje podřízené prvky tohoto bloku ve specifikovaných znacích, například závorkami nebo jinými znaky jako rámování
type: docs
weight: 222
url: /cs/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) metoda


Obalí podřízené prvky tohoto bloku ve specifikovaných znacích, například závorkami nebo jinými znaky jako rámování

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char16_t | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char16_t | Koncový znak (obvykle pravá závorka) |

### Návratová hodnota

Matematický prvek typu [IMathDelimiter](../../imathdelimiter/) zahrnující specifikované znaky jako rámování
## Poznámky



Příklad: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) metoda


Obalí podřízené prvky tohoto bloku ve specifikovaných znacích, například závorkami nebo jinými jako rámování, a oddělí je znakem oddělovače

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char16_t | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char16_t | Koncový znak (obvykle pravá závorka) |
| separatorCharacter | char16_t | Znak oddělovače |

### Návratová hodnota

Matematický prvek typu [IMathDelimiter](../../imathdelimiter/) zahrnující specifikované znaky jako rámování a oddělovač
## Poznámky



Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathDelimiter](../../imathdelimiter/)
* Třída [MathBlock](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)