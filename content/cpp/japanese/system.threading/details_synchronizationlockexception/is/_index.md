---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.threading/details_synchronizationlockexception/is/
---
## 詳細_SynchronizationLockException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Threading::Details_SynchronizationLockException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 構造体は、現在のオブジェクトが比較される型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false を返します。

## 備考

オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。

## 参照

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_SynchronizationLockException](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)