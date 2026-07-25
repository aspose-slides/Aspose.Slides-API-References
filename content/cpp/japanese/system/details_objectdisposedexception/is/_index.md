---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_objectdisposedexception/is/
---
## 詳細_ObjectDisposedException::Is(const System::TypeInfo\&) const メソッド


```cpp
bool System::Details_ObjectDisposedException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 現在のオブジェクトに対してテストする型を記述した構造体。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスの場合は True、そうでない場合は false。

## 備考

オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子に相当します。

## 参照

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_ObjectDisposedException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)