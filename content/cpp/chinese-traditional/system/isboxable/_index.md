---
title: IsBoxable
second_title: Aspose.Slides for C++ API 參考
description: 範本謂詞，用於檢查是否支援指定類型的裝箱。
type: docs
weight: 1665
url: /zh-hant/system/isboxable/
---
## IsBoxable 結構


範本謂詞，用於檢查是否支援指定類型的裝箱。

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 要檢查的類型 |

## 參見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)