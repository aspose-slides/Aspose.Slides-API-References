---
title: Compare()
second_title: Aspose.Slides for C++ API リファレンス
description: 実際のデータ比較。
type: docs
weight: 1
url: /ja/system.collections.generic/defaultcomparer/compare/
---
## DefaultComparer::Compare(typename ThisType::args_type, typename ThisType::args_type) const メソッド


実際のデータ比較。

```cpp
virtual int System::Collections::Generic::DefaultComparer<T, typename>::Compare(typename ThisType::args_type x, typename ThisType::args_type y) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | typename [ThisType::args_type](../../icomparer/args_type/) | 左オペランド。 |
| y | typename [ThisType::args_type](../../icomparer/args_type/) | 右オペランド。 |

### 戻り値

**x** が **y** 未満の場合は負の値、オペランドが等しい場合は 0、その他の場合は正の値を返します。

## 参照

* 型定義 [args_type](../../icomparer/args_type/)
* クラス [DefaultComparer](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)