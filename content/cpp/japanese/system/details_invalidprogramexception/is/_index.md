---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_invalidprogramexception/is/
---
## Details_InvalidProgramException::Is(const System::TypeInfo\&) const メソッド




```cpp
bool System::Details_InvalidProgramException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 現在のオブジェクトに対してテストする型を記述する構造体。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は True、そうでない場合は false。

## 備考

オブジェクトが targetType で記述された型のインスタンスを表すかどうかを確認します。C# の 'is' 演算子に相当します。

## 参照

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_InvalidProgramException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)