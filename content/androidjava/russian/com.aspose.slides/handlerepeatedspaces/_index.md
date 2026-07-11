---
title: HandleRepeatedSpaces
second_title: Aspose.Slides для Android через справку API Java
description: Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте в Markdown.
type: docs
url: /ru/com.aspose.slides/handlerepeatedspaces/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте в Markdown.
## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | Все пробелы сохраняются как обычные пробельные символы без каких-либо изменений. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Преобразует последовательности из двух и более подряд идущих обычных пробелов, чередуя обычные пробельные символы и неразрывные пробелы (NBSP). |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Преобразует последовательности из двух и более подряд идущих обычных пробелов, оставляя первый пробел как обычный пробельный символ и заменяя все последующие пробелы на неразрывные пробелы (NBSP). |
### None {#None}
```
public static final int None
```


Все пробелы сохраняются как обычные пробельные символы без каких-либо изменений. Преобразование не применяется, и несколько подряд идущих пробелов экспортируются без изменений.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


Преобразует последовательности из двух и более подряд идущих обычных пробелов, чередуя обычные пробельные символы и неразрывные пробелы (NBSP). Первый пробел всегда сохраняется как обычный пробел.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


Преобразует последовательности из двух и более подряд идущих обычных пробелов, оставляя первый пробел как обычный пробельный символ и заменяя все последующие пробелы на неразрывные пробелы (NBSP).