---
title: operator!=()
second_title: Aspose.Slides för C++ API-referens
description: Icke-likhetsjämförelseoperator.
type: docs
weight: 313
url: /sv/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const metod


Icke-likhetsjämförelseoperator.

```cpp
bool System::String::operator!=(const String &str) const
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) att jämföra den aktuella med. |

### Returvärde

false om båda strängarna är null eller båda är icke-null och matchar, true annars.

## String::operator!=(std::nullptr_t) const metod


Kontrollerar om strängen inte är null. Tillämpar samma logik som [IsNull()](../isnull/) anrop.

```cpp
bool System::String::operator!=(std::nullptr_t) const
```


### Returvärde

false om strängen är null, true annars.

## Se också

* Klass [String](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)