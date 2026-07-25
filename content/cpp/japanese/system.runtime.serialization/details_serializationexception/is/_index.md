---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.runtime.serialization/details_serializationexception/is/
---
## 詳細_SerializationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Runtime::Serialization::Details_SerializationException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 構造体は、現在のオブジェクトに対してテストする型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考


targetType によって記述された型のインスタンスであるかどうかをオブジェクトが表すか確認します。C# の 'is' 演算子の類似です。

## 参照

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_SerializationException](../)
* 名前空間 [System::Runtime::Serialization](../../)
* ライブラリ [Aspose.Slides](../../../)