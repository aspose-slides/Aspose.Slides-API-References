---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: targetType で記述された型のインスタンスを表すオブジェクトかどうかを確認します。C# の 'is' 演算子に相当します。
type: docs
weight: 222
url: /ja/system/object/is/
---
## Object::Is(const TypeInfo\&) const メソッド

オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の類似です。

```cpp
virtual bool System::Object::Is(const TypeInfo &targetType) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetType | const [TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 構造体は、現在のオブジェクトをテストする対象の型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false を返します。

## 参照

* クラス [TypeInfo](../../typeinfo/)
* クラス [Object](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)