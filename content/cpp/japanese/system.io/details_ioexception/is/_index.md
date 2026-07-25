---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.io/details_ioexception/is/
---
## Details_IOException::Is(const System::TypeInfo\&) const method




```cpp
bool System::IO::Details_IOException::Is(const System::TypeInfo &target) const override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 構造体は、現在のオブジェクトに対してテストする型を記述します。 |

### 戻り値

True if object is of tagged type or its subclass, false otherwise.

## 備考

オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子に相当します。

## 関連項目

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_IOException](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)