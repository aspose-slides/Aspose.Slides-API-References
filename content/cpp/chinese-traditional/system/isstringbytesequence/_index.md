---
title: IsStringByteSequence
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 用於檢查類型是否為字串字符序列的模板魔法。
type: docs
weight: 1717
url: /zh-hant/system/isstringbytesequence/
---
## IsStringByteSequence 結構

模板魔法，用於檢查類型是否為字串字符序列。

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 被檢查的類型。 |
| CharT | 要檢查的字符類型。 |

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)