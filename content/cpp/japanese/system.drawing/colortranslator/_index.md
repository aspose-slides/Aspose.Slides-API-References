---
title: ColorTranslator
second_title: Aspose.Slides for C++ API リファレンス
description: "カラーの変換を実行します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 66
url: /ja/system.drawing/colortranslator/
---
## ColorTranslator クラス

指定されたカラーの変換を実行します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class ColorTranslator
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | 指定された HTML カラー表現を同等の [Color](../color/) オブジェクトに変換します。 |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | 指定された [Windows](../../system.windows/) カラーを同等の [Color](../color/) オブジェクトに変換します。 |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | 指定された [Color](../color/) オブジェクトを同等の HTML カラーの文字列表現に変換します。 |

## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)