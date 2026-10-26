---
title: Replace()
second_title: Aspose.Slides for C++ API 參考
description: 透過生成器取代子字串。
type: docs
weight: 196
url: /zh-hant/system.text/stringbuilder/replace/
---
## StringBuilder::Replace(const String\&, const String\&) 方法

透過生成器取代子字串。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) 以取代。 |
| newString | const [String](../../../system/string/)\& | 替換字串。 |

### 返回值

此指標。

## StringBuilder::Replace(const String\&, const String\&, int, int) 方法

透過生成器的範圍取代子字串。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString, int position, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) 以取代。 |
| newString | const [String](../../../system/string/)\& | 替換字串。 |
| position | int | 生成器取代範圍的起始位置。 |
| count | int | 生成器取代範圍的長度。 |

### 返回值

此指標。

## StringBuilder::Replace(char_t, char_t) 方法

透過生成器取代字元。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oldChar | char_t | 要取代的字元。 |
| newChar | char_t | 替換字元。 |

### 返回值

此指標。

## StringBuilder::Replace(char_t, char_t, int, int) 方法

透過生成器的範圍取代字元。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar, int startIndex, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oldChar | char_t | 要取代的字元。 |
| newChar | char_t | 替換字元。 |
| startIndex | int | 生成器取代範圍的起始位置。 |
| count | int | 生成器取代範圍的長度。 |

### 返回值

此指標。

## 另請參閱

* 類別 [StringBuilder](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)