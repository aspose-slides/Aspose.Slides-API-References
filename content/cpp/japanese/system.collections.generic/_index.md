---
title: "System::Collections::Generic"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 326
url: /ja/system.collections.generic/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [_KeyCollection](./_keycollection/) | [Dictionary](./dictionary/) のキーのコレクション。コレクションへの参照であり、何もコピーしません。 このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [_KeyList](./_keylist/) | 辞書のキーのリストを実装します。 このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [_ValueCollection](./_valuecollection/) | [Dictionary](./dictionary/) の値のコレクション。コレクションへの参照であり、何もコピーしません。 このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [_ValueList](./_valuelist/) | 辞書の値のリストを実装します。 このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [BaseDictionary](./basedictionary/) | さまざまな辞書類似データ構造（例: [Dictionary](./dictionary/)、[SortedDictionary](./sorteddictionary/)）の共通コードを実装します。直接使用すべきではなく、コンテナを定義するときの継承以外では使用しません。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [BaseEnumerator](./baseenumerator/) | STL 形式の型を C# 形式で使用できるようにラップする列挙子定義です。逐次イテレータが存在すること以外、コンテナ構造に対してアサーションを行いません。begin() と end() 関数を使用します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [BaseKVCollection](./basekvcollection/) | キーまたは値のコレクションの共通コードを保持します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [BaseSet](./baseset/) |  |
| [Comparer](./comparer/) | [System.Collections.Generic.IComparer](./icomparer/) ジェネリックインターフェイスの実装のための基底クラスを提供します。 |
| [DefaultComparer](./defaultcomparer/) | デフォルト比較クラスです。operator < と operator == を使用して値を比較します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [Details_KeyNotFoundException](./details_keynotfoundexception/) |  |
| [Dictionary](./dictionary/) | [Dictionary](./dictionary/) クラスの前方宣言です。 |
| [DictionaryIterator](./dictionaryiterator/) | [Dictionary](./dictionary/) イテレータで、[KeyValuePair](./keyvaluepair/) 表記を提供します。 |
| [DictionaryPtr](./dictionaryptr/) | [Dictionary](./dictionary/) ポインタクラスで、演算子オーバーロードを備えています。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。 |
| [EnumerableExt](./enumerableext/) |  |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/) | 事前に作成された列挙子をラップし、すべての呼び出しをそれにリダイレクトするイテレータです。 |
| [HashDictionary](./hashdictionary/) | [HashDictionary](./hashdictionary/) クラスのスタブです（現在実装されていません）。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [HashSet](./hashset/) | [HashSet](./hashset/) クラスの前方宣言です。 |
| [HashSetPtr](./hashsetptr/) | [HashSet](./hashset/) 参照を保持するポインタです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。 |
| [ICollection](./icollection/) | 要素のコレクションのインターフェイスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [IComparer](./icomparer/) | 2つのオブジェクトを大なり・等しい・小なりの意味で比較するインターフェイスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [IDictionary](./idictionary/) | 辞書類似コンテナ用インターフェイスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [IEnumerable](./ienumerable/) | 含まれる要素に対して列挙子を提供するオブジェクトのインターフェイスです。 |
| [IEnumerator](./ienumerator/) | いくつかの要素を反復処理できる列挙子のインターフェイスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [IEqualityComparer](./iequalitycomparer/) | 2つのオブジェクトの等価性を比較する手段を提供するインターフェイスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [IKVCollection](./ikvcollection/) | 辞書類似コンテナのキーまたは値を含むコンテナのインターフェイスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [IList](./ilist/) | 要素のインデックス付きコンテナのインターフェイスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [ISet](./iset/) | ユニークな要素の集合を含むコレクションのインターフェイスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [KeyIterator](./keyiterator/) | [Dictionary](./dictionary/) イテレータで、キーアクセスを提供します。 |
| [KeyValuePair](./keyvaluepair/) | キーと値のペアです。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。この型のオブジェクトを管理するために [System::SmartPtr](../system/smartptr/) クラスを使用しないでください。 |
| [KVPairIterator](./kvpairiterator/) | 適応イテレータで、std::pair を [Dictionary](./dictionary/) が期待する KVPair にラップします。 |
| [LinkedList](./linkedlist/) | [LinkedList](./linkedlist/) の前方宣言です。 |
| [LinkedListNode](./linkedlistnode/) | リンクドリストのノードです。リンクドリストでラップされた std::list のイテレータ上のラッパーを実装します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [List](./list/) | [List](./list/) の前方宣言です。 |
| [ListExt](./listext/) | [IListWrapper](../system.collections/ilistwrapper/) インターフェイスを実装する汎用 [List](./list/) クラスです。 |
| [ListPtr](./listptr/) | [List](./list/) ポインタで、アクセス演算子を提供します。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。 |
| [Queue](./queue/) | [Queue](./queue/) クラスの前方宣言です。 |
| [QueuePtr](./queueptr/) | [Queue](./queue/) ポインタです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。 |
| [ReverseEnumerator](./reverseenumerator/) | コンテナを逆順に反復する列挙子です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [SimpleEnumerator](./simpleenumerator/) | rbegin() と rend() 関数を使用して要素を直接保持するシンプルコンテナ用イテレータクラスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [SortedDictionary](./sorteddictionary/) | ソートされた辞書型の前方宣言です。 |
| [SortedDictionaryPtr](./sorteddictionaryptr/) | ソートされた辞書のポインタで、アクセス演算子を提供します。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。 |
| [SortedList](./sortedlist/) | FlatMap 構造体をラップするソート済みリストです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上または operator new を使用してこの型のインスタンスを作成しないでください。ランタイムエラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。 |
| [SortedListHelper](./sortedlisthelper/) | このヘルパークラスは、[IDictionary](./idictionary/) インターフェイスから来る仮想関数 get_Keys、get_Values を隠蔽し、異なる戻り値型の関数に置き換えるために使用されます。 |
| [SortedSet](./sortedset/) | [SortedSet](./sortedset/) クラスの前方宣言です。 |
| [SortedSetPtr](./sortedsetptr/) | [SortedSet](./sortedset/) 参照を保持するポインタです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。 |
| [Stack](./stack/) | [Stack](./stack/) クラスの前方宣言です。 |
| [StackPtr](./stackptr/) | [Stack](./stack/) ポインタです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。 |
| [ValueIterator](./valueiterator/) | [Dictionary](./dictionary/) イテレータで、値アクセスを提供します。 |

## 構造体

| 構造体 | 説明 |
| --- | --- |
| [ComparerAdapter](./compareradapter/) | STL 環境で [IComparer](./icomparer/) を使用するためのアダプタです。[IComparer](./icomparer/) が設定されている場合はそれを使用し、設定されていない場合は operator <（利用可能な場合）を使用するか、利用できない場合は false を返します。 |
| [DictionaryHashSelector](./dictionaryhashselector/) | [Dictionary](./dictionary/) クラスのハッシュ関数セレクタです。代替手段が提供されていない場合、この実装は STL のハッシュを使用します。 |
| [EqualityComparerAdapter](./equalitycompareradapter/) | STL 形式のコレクションとアルゴリズムで [IEqualityComparer](./iequalitycomparer/) を使用可能にするアダプタです。[IEqualityComparer](./iequalitycomparer/) が設定されている場合はそれを使用します。設定されていない場合は、利用可能な operator ==、[Object::Equals](../system/object/equals/)、または T::Equals のいずれかを使用します。 |
| [EqualityComparerHashAdapter](./equalitycomparerhashadapter/) | ハッシュ化のために [IEqualityComparer](./iequalitycomparer/) を使用するアダプタです。コンパレータオブジェクトが設定されている場合はそれを使用し、設定されていない場合は [DictionaryHashSelector](./dictionaryhashselector/) 構造体で選択された利用可能なハッシュメソッドを使用します。 |

## 関数

| 関数 | 説明 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 2つのキーと値のペアを 'equals' セマンティクスで比較します。キーと値の両方に対して、定義されている方の operator == または EqualsTo メソッドを使用します。 |
| **bool** [operator!=](./operator_not_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 2つのキーと値のペアを逆の 'equals' セマンティクスで比較します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | UTF-8 エンコードを使用してストリームにデータを挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | ストリームにデータを挿入します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [KeyNotFoundException](./keynotfoundexception/) |  |