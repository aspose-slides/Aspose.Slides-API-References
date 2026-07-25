---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_memberaccessexception/is/
---
## Details_MemberAccessException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_MemberAccessException::Is(const System::TypeInfo &target) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 現在のオブジェクトがテスト対象とする型を記述する構造体。 |

### 戻り値

タグ付けされた型またはそのサブクラスであれば true、そうでなければ false。

## 備考

targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子に相当します。

## 関連項目

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_MemberAccessException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)