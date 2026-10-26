---
title: "System::Text::RegularExpressions"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 989
url: /ja/system.text.regularexpressions/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [Capture](./capture/) | 単一のサブ式マッチングの結果です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [CaptureCollection](./capturecollection/) | 単一のキャプチャグループによって取得されたキャプチャのリストです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [Group](./group/) | 単一のキャプチャグループによって行われたマッチの結果です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [GroupCollection](./groupcollection/) | 単一のマッチに含まれるキャプチャグループのリストです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) コレクションポインタ。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。 |
| [Match](./match/) | [Single](../system/single/) の文字列に対する正規表現マッチです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [MatchCollection](./matchcollection/) | 文字列に対して正規表現を繰り返し適用して得られるマッチのコレクションです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [Regex](./regex/) | C# ライク構文に従う正規表現です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
## 関数

| 関数 | 説明 |
| --- | --- |
|  [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | MatchHolder クラスと PCRE2 のインクルードなしで保持するためのラッパーです。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) オプション。 |
## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [UStringPtr](./ustringptr/) | コピーを回避するための共有 UnicodeString。 |
| [CapturePtr](./captureptr/) | 単一キャプチャオブジェクトへのポインタ。 |
| [CaptureCollectionPtr](./capturecollectionptr/) | キャプチャコレクションへのポインタ。 |
| [GroupPtr](./groupptr/) | グループへのポインタ。 |
| [RegexPtr](./regexptr/) | [Regex](./regex/) ポインタ。 |
| [MatchPtr](./matchptr/) | [Match](./match/) ポインタ。 |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) コレクションポインタ。 |
| [MatchEvaluator](./matchevaluator/) | マッチを評価するデリゲート型。 |