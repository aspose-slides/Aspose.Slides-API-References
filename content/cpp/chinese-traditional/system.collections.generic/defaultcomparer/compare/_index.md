---
title: Compare()
second_title: Aspose.Slides for C++ API 參考文件
description: 實際資料比較。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/defaultcomparer/compare/
---
## DefaultComparer::Compare(typename ThisType::args_type, typename ThisType::args_type) const method


實際的資料比較。

```cpp
virtual int System::Collections::Generic::DefaultComparer<T, typename>::Compare(typename ThisType::args_type x, typename ThisType::args_type y) const override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | typename [ThisType::args_type](../../icomparer/args_type/) | 左側運算元。 |
| y | typename [ThisType::args_type](../../icomparer/args_type/) | 右側運算元。 |

### 返回值

如果 **x** 小於 **y**，則返回負值；如果運算元相等則返回 0，否則返回正值。

## 另請參閱

* 型別別名 [args_type](../../icomparer/args_type/)
* 類別 [DefaultComparer](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)