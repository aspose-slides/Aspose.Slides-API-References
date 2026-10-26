---
title: SmartPtrInfo
second_title: Aspose.Slides for C++ API リファレンス
description: 最終型を知らなくても SmartPtr の内容をテストおよび変更するためのサービスクラスです。ガベージコレクションやループ参照検出などに使用されます。'pointer to pointer' と考えてください。SmartPtr の基底型は存在しないため使用できず、代わりにこの 'info' クラスを使用します。
type: docs
weight: 1249
url: /ja/system/smartptrinfo/
---
## SmartPtrInfo クラス

Service class to test and alter [SmartPtr](../smartptr/)'s contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of 'pointer to pointer'. We can't use [SmartPtr](../smartptr/)'s basetype as it doesn't have any; instead, we use this 'info' class.

```cpp
class SmartPtrInfo
```

## メソッド

| Method | Description |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | 参照されたポインタが指す生のオブジェクトを取得します。 |
| [Object](../object/) * [getObject](./getobject/)() const | 参照されたポインタが指すオブジェクトを取得します。 |
| [Object](../object/) * [getOwned](./getowned/)() const | 所有オブジェクトのポインタを取得します。 |
|  [operator bool](./operator_bool/)() const | info オブジェクトが非 null ポインタを指しているか確認します。 |
| **bool** [operator!](./operator_not/)() const | info オブジェクトが非 null ポインタを指していないか確認します。 |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | 参照されたポインタが指す [Object](../object/) のメソッドを呼び出すことができます。 |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | 2つの info オブジェクトが参照するポインタの値を小比較します。 |
|  [SmartPtrInfo](./smartptrinfo/)() | 空の [SmartPtrInfo](./) オブジェクトを作成します。 |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | 特定のスマートポインタに関する情報を持つ [SmartPtrInfo](./) オブジェクトを作成します。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)