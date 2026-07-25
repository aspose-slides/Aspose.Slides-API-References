---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_typeinitializationexception/is/
---
## 詳細_TypeInitializationException::Is(const System::TypeInfo\&) const メソッド

```cpp
bool System::Details_TypeInitializationException::Is(const System::TypeInfo &target) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 構造体で、現在のオブジェクトがテスト対象とする型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考

対象の型で記述された型のインスタンスをオブジェクトが表すかどうかを確認します。C# の 'is' 演算子の類似です。

## 参照

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_TypeInitializationException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)