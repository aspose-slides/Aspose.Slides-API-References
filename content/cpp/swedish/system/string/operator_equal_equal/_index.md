---
title: operator==()
second_title: Aspose.Slides för C++ API-referens
description: Likhetsjämförelseoperator.
type: docs
weight: 300
url: /sv/system/string/operator_equal_equal/
---
## String::operator==(const String&) const metod

Likhetsjämförelseoperator.

```cpp
bool System::String::operator==(const String &str) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) för att jämföra den aktuella med. |

### Returvärde

true if both strings are null or both are not null and match, false otherwise.

## String::operator==(std::nullptr_t) const metod

Kontrollerar om strängen är null. Använder samma logik som [IsNull()](../isnull/) anrop.

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### Returvärde

true if string is null, false otherwise.

## Se även

* Klass [String](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)