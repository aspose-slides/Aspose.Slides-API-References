---
title: IsStringLiteral
second_title: Aspose.Slides for C++ API 參考
description: 用於檢查類型是否為字串字面值的模板魔法。
type: docs
weight: 1730
url: /zh-hant/system/isstringliteral/
---
## IsStringLiteral struct

模板魔法，用於檢查類型是否為字串字面值。

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 被檢查的類型。 |
| CharT | 要檢查的字元類型。 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)