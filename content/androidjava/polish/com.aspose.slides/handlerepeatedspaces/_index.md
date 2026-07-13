---
title: HandleRepeatedSpaces
second_title: Aspose.Slides dla Androida w interfejsie API Java
description: Określa, jak należy obsługiwać powtarzające się zwykłe znaki spacji podczas eksportu Markdown.
type: docs
url: /pl/com.aspose.slides/handlerepeatedspaces/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Określa, jak należy obsługiwać powtarzające się zwykłe znaki spacji podczas eksportu Markdown.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Wszystkie spacje są zachowywane jako zwykłe znaki spacji bez żadnych zmian. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Konwertuje sekwencje dwóch lub więcej kolejnych zwykłych spacji, naprzemiennie zamieniając je na zwykłe znaki spacji i jednostki niełamiącej spacji (NBSP). |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Konwertuje sekwencje dwóch lub więcej kolejnych zwykłych spacji, zachowując pierwszą spację jako zwykły znak spacji, a wszystkie kolejne spacje zastępując jednostkami niełamiącej spacji (NBSP). |
### None {#None}
```
public static final int None
```

Wszystkie spacje są zachowywane jako zwykłe znaki spacji bez żadnych zmian. Nie stosuje się żadnej transformacji, a wiele kolejnych spacji jest eksportowanych w takiej formie.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Konwertuje sekwencje dwóch lub więcej kolejnych zwykłych spacji, naprzemiennie zamieniając je na zwykłe znaki spacji i jednostki niełamiącej spacji (NBSP). Pierwsza spacja jest zawsze zachowywana jako zwykła spacja.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Konwertuje sekwencje dwóch lub więcej kolejnych zwykłych spacji, zachowując pierwszą spację jako zwykły znak spacji i zastępując wszystkie kolejne spacje jednostkami niełamiącej spacji (NBSP).