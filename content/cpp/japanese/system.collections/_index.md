---
title: "System::Collections"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 300
url: /ja/system.collections/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) はインデックスでアクセス可能なビットの集合です。 このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上や operator new を使ってこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [BitArrayPtr](./bitarrayptr/) | [BitArray](./bitarray/) へのポインタ。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数へは値渡しまたは const 参照で渡すべきです。 |
| [CollectionBase](./collectionbase/) | 強く型付けされたコレクションの抽象基底クラスを提供します。 |
| [ICollection](./icollection/) | 非ジェネリックコレクションインターフェイスを定義します。 |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) は列挙可能なすべての非ジェネリックコレクションの基底インターフェイスです。 |
| [IEnumerator](./ienumerator/) | いくつかの要素を反復処理できる列挙子のインターフェイス。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | ジェネリックイテレータ [IEnumeratorImplRefType](./ienumeratorimplreftype/) 上に非ジェネリック [IEnumerator](./ienumerator/) 実装を作成するラッパーです — 参照型用ラッパー。 |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | ジェネリックイテレータ [IEnumeratorImplRefType](./ienumeratorimplreftype/) 上に非ジェネリック [IEnumerator](./ienumerator/) 実装を作成するラッパーです — 値型用ラッパー。 |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) はインデックスで個別にアクセス可能なオブジェクトの非ジェネリックコレクションを表します。 |
| [IListImplRefType](./ilistimplreftype/) | [System::Collections::Generic::List](../system.collections.generic/list/) オブジェクト上で [System::Collections::IList](./ilist/) インターフェイスを実装するスタブです。参照型向け実装。 |
| [IListImplValueType](./ilistimplvaluetype/) | [System::Collections::Generic::List](../system.collections.generic/list/) オブジェクト上で [System::Collections::IList](./ilist/) インターフェイスを実装するスタブです。値型向け実装。 |
| [IListWrapper](./ilistwrapper/) | ジェネリックから非ジェネリックコレクションへのキャストをサポートするインターフェイス。 |
| [Invalidatable](./invalidatable/) | [InvalidatableTracker](./invalidatabletracker/) オブジェクトを通じて子孫の状態を追跡できるクラスです。 |
| [InvalidatableTracker](./invalidatabletracker/) | [Invalidatable](./invalidatable/) オブジェクトのトラッカーを実装するクラスです。 |