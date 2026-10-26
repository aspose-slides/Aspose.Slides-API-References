---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.threading/details_threadinterruptedexception/is/
---
## Details_ThreadInterruptedException::Is(const System::TypeInfo\&) const メソッド

```cpp
bool System::Threading::Details_ThreadInterruptedException::Is(const System::TypeInfo &target) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 構造体は、現在のオブジェクトに対してテストする型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでなければ false。

## 備考

オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子に相当します。

## 関連項目

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_ThreadInterruptedException](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)