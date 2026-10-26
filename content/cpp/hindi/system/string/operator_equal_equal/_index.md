---
title: operator==()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: समता तुलना ऑपरेटर।
type: docs
weight: 300
url: /hi/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const मेथड

Equality comparison operator. को हिंदी में "समता तुलना ऑपरेटर।" कहा जाएगा।

```cpp
bool System::String::operator==(const String &str) const
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) वर्तमान को तुलना करने के लिए। |

### रिटर्न मान

true if both strings are null or both are not null and match, false otherwise.

## String::operator==(std::nullptr_t) const मेथड

Checks if string is null. Applies same logic as [IsNull()](../isnull/) call.

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### रिटर्न मान

true if string is null, false otherwise.

## संबंधित देखें

* क्लास [String](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)