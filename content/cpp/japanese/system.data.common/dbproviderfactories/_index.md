---
title: DbProviderFactories
second_title: Aspose.Slides for C++ API リファレンス
description: "DB プロバイダー ファクトリを取得するための API。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てる必要があります。この型のインスタンスをスタック上で、または operator new を使用して作成しないでください。実行時エラーやアサーション違反が発生する可能性があります。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡してください。"
type: docs
weight: 53
url: /ja/system.data.common/dbproviderfactories/
---
## DbProviderFactories クラス

DB プロバイダー ファクトリを取得するための API。 このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てる必要があります。 この型のインスタンスをスタック上で、または operator new を使用して作成しないでください。 実行時エラーやアサーション違反が発生する可能性があります。 常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。

```cpp
class DbProviderFactories
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | 名前で DB プロバイダー ファクトリを取得します。 |

## 参照

* 名前空間 [System::Data::Common](../)
* ライブラリ [Aspose.Slides](../../)