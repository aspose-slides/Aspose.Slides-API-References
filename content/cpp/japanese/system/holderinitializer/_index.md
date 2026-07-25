---
title: HolderInitializer
second_title: Aspose.Slides for C++ API リファレンス
description: このクラスは、オブジェクト インスタンスへの永続的な参照を取得するために使用されます。対象が lvalue であろうと rvalue であろうとです。そのような参照を取得するには、'HoldIfTemporary' メソッドを使用します。このメソッドには 3 つのオーバーロードがあります。そのうち 2 つは rvalue をパラメータとして受け取り、単にその参照を返します。3 つ目は逆に lvalue をパラメータとして受け取り、ポインタのコピーを作成し、そのコピーへの参照を返します。また、クラスには渡された値を無条件に保持する 'Hold' メソッドがあり（ローカルのスタック変数やその子参照の値をコピーするために使用されます）。
type: docs
weight: 1639
url: /ja/system/holderinitializer/
---
## HolderInitializer struct

このクラスは、オブジェクト インスタンスへの永続的な参照を取得するために使用されます。対象が lvalue であろうと rvalue であろうとです。このような参照を取得するには、'HoldIfTemporary' メソッドを使用します。このメソッドには 3 つのオーバーロードがあります。そのうち 2 つは rvalue をパラメータとして受け取り、その参照を返します。3 つ目は逆に lvalue をパラメータとして受け取り、ポインタのコピーを作成し、そのコピーへの参照を返します。また、クラスには 'Hold' メソッドがあり、渡された値を無条件に保持します（ローカルのスタック変数やその子参照の値をコピーするために使用されます）。

```cpp
template<typename T,bool>class HolderInitializer
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | 保持するオブジェクトの型。 |
| R | T が参照型（[SmartPtr](../smartptr/) の特殊化または [System::String](../string/) 型）の場合は true で、一時的な参照の保持が実際に必要な場合です。それ以外の場合は false。 |

## メソッド

| Method | Description |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | 渡された lvalue をホルダーにコピーし、ホルダーへの参照を返します。呼び出し側はこのメソッドを使用して、渡された値を無条件に保持すべきです。 |
|  [HolderInitializer](./holderinitializer/)(T\&) | 渡された参照でホルダー参照を初期化します。 |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | rvalue（const）の参照を返します。 |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | rvalue（非 const）の参照を返します。 |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | 渡された lvalue をホルダーにコピーし、ホルダーへの参照を返します。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)