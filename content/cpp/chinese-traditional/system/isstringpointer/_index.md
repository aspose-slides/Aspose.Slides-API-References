---
title: IsStringPointer
second_title: Aspose.Slides for C++ API 參考文件
description: 模板技巧，用於檢查類型是否為字元字串指標。
type: docs
weight: 1743
url: /zh-hant/system/isstringpointer/
---
## IsStringPointer 結構

模板技巧，用於檢查類型是否為字元字串指標。

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 被檢查的型別。 |
| CharT | 要檢查的字元型別。 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)