---
title: WeakReference<>
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクトを参照しながら、そのオブジェクトが削除されることを可能にする弱参照を表します。
type: docs
weight: 1522
url: /ja/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> クラス


Represents a weak reference, which references an object while still allowing that object to be deleted.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | 現在の WeakReference オブジェクトが参照しているオブジェクトが削除されたかどうかのインジケータを取得します。 |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | 現在の WeakReference オブジェクトが参照しているオブジェクト (対象) を取得します。 |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 現在の WeakReference オブジェクトが参照しているオブジェクト (対象) を設定します。 |
|  [WeakReference](./weakreference/)() | デフォルトコンストラクタ。 |
|  [WeakReference](./weakreference/)(std::nullptr_t) | nullptr からのコンストラクタ。 |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 指定されたオブジェクトを参照する WeakReference クラスの新しいインスタンスを初期化します。 |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | 指定されたオブジェクトを参照する WeakReference クラスの新しいインスタンスを初期化します。 |
## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)