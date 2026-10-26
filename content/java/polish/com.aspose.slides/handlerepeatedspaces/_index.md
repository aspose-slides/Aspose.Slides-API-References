---
title: HandleRepeatedSpaces
second_title: Aspose.Slides - dokumentacja API dla Javy
description: Określa, jak należy obsługiwać powtarzające się regularne znaki spacji podczas eksportu Markdown.
type: docs
url: /pl/com.aspose.slides/handlerepeatedspaces/
---
**Inheritance:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum  
```
public final class HandleRepeatedSpaces extends System.Enum
```

Określa, jak należy obsługiwać powtarzające się regularne znaki spacji podczas eksportu Markdown.

## Pola

| Pole | Opis |
| --- | --- |
| [None](#None) | Wszystkie spacje są zachowywane jako regularne znaki spacji bez żadnych zmian. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Konwertuje ciągi dwóch lub więcej kolejnych regularnych spacji, naprzemiennie używając regularnych znaków spacji i znaków niełamliwych spacji NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Konwertuje ciągi dwóch lub więcej kolejnych regularnych spacji, zachowując pierwszą spację jako regularny znak spacji i zamieniając wszystkie kolejne spacje na znaki niełamliwych spacji NBSP. |

### None {#None}
```
public static final int None
```

Wszystkie spacje są zachowywane jako regularne znaki spacji bez żadnych zmian. Nie stosuje się żadnej transformacji, a wiele kolejnych spacji jest eksportowanych w takiej formie.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Konwertuje ciągi dwóch lub więcej kolejnych regularnych spacji, naprzemiennie używając regularnych znaków spacji i znaków niełamliwych spacji NBSP. Pierwsza spacja jest zawsze zachowywana jako regularna spacja.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Konwertuje ciągi dwóch lub więcej kolejnych regularnych spacji, zachowując pierwszą spację jako regularny znak spacji i zamieniając wszystkie kolejne spacje na znaki niełamliwych spacji NBSP.