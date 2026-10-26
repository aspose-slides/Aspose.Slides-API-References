---
title: Enclose()
second_title: Aspose.Slides pro C++ – reference API
description: Uzavře podřízené prvky tohoto bloku do zadaných znaků, například závorek, nebo jiných, jako rámcování a oddělí je znakem oddělovače
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) method

Uzavře podřízené prvky tohoto bloku do zadaných znaků, například závorek, nebo jiných, jako rámcování a oddělí je znakem oddělovače

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char16_t | Koncový znak (obvykle pravá závorka) |
| separatorCharacter | char16_t | Oddělovací znak |

### Return Value

Matematický prvek typu [IMathDelimiter](../../imathdelimiter/), který obsahuje zadané znaky jako rámec a oddělovač

## Remarks

Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathDelimiter](../../imathdelimiter/)
* Třída [IMathBlock](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)