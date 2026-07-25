---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_rankexception/is/
---
## 詳細_RankException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_RankException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 構造体で、現在のオブジェクトをテストする対象の型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考

target が記述する型のインスタンスであるかどうかを確認します。C# の `is` 演算子に相当します。

## 関連項目

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_RankException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)