---
title: CharacterRange
second_title: Aspose.Slides for C++ API リファレンス
description: "文字列内の文字位置の範囲を表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 40
url: /ja/system.drawing/characterrange/
---
## CharacterRange クラス

文字列内の文字位置の範囲を表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class CharacterRange
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | [CharacterRange](./) クラスの新しいインスタンスを構築し、指定された範囲を表します。 |
|  [CharacterRange](./characterrange/)() | [CharacterRange](./) クラスの新しいインスタンスを構築し、空の範囲を表します。 |
| **int32_t** [get_First](./get_first/)() const | 現在のオブジェクトが表す範囲の最初の文字の位置を返します。 |
| **int32_t** [get_Length](./get_length/)() const | 現在のオブジェクトが表す範囲の文字数を返します。 |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが異なる範囲を表すかどうかを判定します。 |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが同じ範囲を表すかどうかを判定します。 |
| void [set_First](./set_first/)(**int32_t**) | 現在のオブジェクトが表す範囲の最初の文字の位置を設定します。 |
| void [set_Length](./set_length/)(**int32_t**) | 現在のオブジェクトが表す範囲の文字数を返します。 |

## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)