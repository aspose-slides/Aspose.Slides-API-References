---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 794
url: /ja/system.runtime.serialization/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) インターフェイスの基本実装を表します。 |
| [IFormatterConverter](./iformatterconverter/) | [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) のインスタンスと、[System::Runtime::Serialization::SerializationInfo](./serializationinfo/) 内のデータを解析するのに最適な、フォーマッタ提供のクラスとの接続を提供します。 |
| [ISerializable](./iserializable/) | シリアライズ可能なオブジェクトのインターフェイス。 このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てる必要があります。 スタック上や operator new を使用してこの型のインスタンスを作成してはいけません。実行時エラーやアサーション失敗の原因になります。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [SerializationInfo](./serializationinfo/) | シリアライズされたオブジェクトを表す名前付きフィールドのセットを保持します。 実装されていません。 このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てる必要があります。 スタック上や operator new を使用してこの型のインスタンスを作成してはいけません。実行時エラーやアサーション失敗の原因になります。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [StreamingContext](./streamingcontext/) | StreamingContext を使用する翻訳済みクラスのコンパイルを可能にするダミークラスです。[SmartPtr](../system/smartptr/) でこのクラスのインスタンスを管理しないでください。スタック上でのみ割り当てる必要があります。 |
## タイプ定義

| タイプ定義 | 説明 |
| --- | --- |
| [SerializationException](./serializationexception/) |  |