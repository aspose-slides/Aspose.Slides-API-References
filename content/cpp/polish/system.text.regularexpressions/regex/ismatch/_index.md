---
title: IsMatch()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Sprawdza dopasowanie wyrażenia regularnego do łańcucha.
type: docs
weight: 53
url: /pl/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String&, int) metoda

Sprawdza dopasowanie wyrażenia regularnego do łańcucha.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch docelowy. |
| startat | int | Indeks początkowy. |

### Wartość zwracana

True jeśli łańcuch pasuje do wyrażenia regularnego, false w przeciwnym razie.

## Regex::IsMatch(const String&, const String&, RegexOptions, TimeSpan, int) metoda

Sprawdza, czy łańcuch pasuje do wzorca.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Łańcuch wejściowy. |
| pattern | const [String](../../../system/string/)\& | Wzorzec wyrażenia regularnego. |
| options | [RegexOptions](../../regexoptions/) | Opcje dopasowania. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Limit czasu. |
| startat | int | [Match](../../match/) pozycja początkowa. |

### Wartość zwracana

True jeśli dopasowanie zostanie znalezione, false w przeciwnym razie.

## Zobacz również

* Enum [RegexOptions](../../regexoptions/)
* Klasa [String](../../../system/string/)
* Klasa [Regex](../)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Text::RegularExpressions](../../)
* Biblioteka [Aspose.Slides](../../../)