---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.threading/details_threadabortexception/is/
---
## Details_ThreadAbortException::Is(const System::TypeInfo\&) const メソッド




```cpp
bool System::Threading::Details_ThreadAbortException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 現在のオブジェクトに対してテストする型を記述する構造体。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考

オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子に相当します。

## 参照

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_ThreadAbortException](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)