---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.threading/details_threadstateexception/is/
---
## Details_ThreadStateException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Threading::Details_ThreadStateException::Is(const System::TypeInfo &target) const override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) は、現在のオブジェクトに対してテストする型を記述する構造体です。 |

### 戻り値

True if object is of tagged type or its subclass, false otherwise.

## 備考


オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。

## 関連項目

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_ThreadStateException](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)