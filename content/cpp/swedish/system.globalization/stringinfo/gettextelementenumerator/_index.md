---
title: GetTextElementEnumerator()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en enumerator för att iterera genom strängens tecken.
type: docs
weight: 118
url: /sv/system.globalization/stringinfo/gettextelementenumerator/
---
## StringInfo::GetTextElementEnumerator(const String\&) metod


Creates enumerator to iterate through string's characters.

```cpp
static SharedPtr<TextElementEnumerator> System::Globalization::StringInfo::GetTextElementEnumerator(const String &str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) för att iterera igenom. |

### Returvärde

Newly created enumerator.

## StringInfo::GetTextElementEnumerator(const String\&, int) metod


Creates enumerator to iterate through string's characters starting at the specified index.

```cpp
static SharedPtr<TextElementEnumerator> System::Globalization::StringInfo::GetTextElementEnumerator(const String &str, int index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) för att iterera igenom. |
| index | int | Startindex. |

### Returvärde

Newly created enumerator.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [TextElementEnumerator](../../textelementenumerator/)
* Klass [String](../../../system/string/)
* Klass [StringInfo](../)
* Namnrymd [System::Globalization](../../)
* Bibliotek [Aspose.Slides](../../../)