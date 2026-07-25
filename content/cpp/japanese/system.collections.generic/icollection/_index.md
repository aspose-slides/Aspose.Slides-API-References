---
title: ICollection
second_title: Aspose.Slides for C++ API リファレンス
description: "要素のコレクションのインターフェイスです。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生する可能性があります。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡して使用してください。"
type: docs
weight: 248
url: /ja/system.collections.generic/icollection/
---
## ICollection クラス

要素のコレクションのインターフェイスです。[System::MakeObject()](../../system/makeobject/) 関数を使用してのみ、このクラスのオブジェクトを割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。これらは実行時エラーやアサーション違反を引き起こす可能性があります。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。

```cpp
template<typename T>class ICollection : public virtual System::Collections::Generic::IEnumerable<T>
```

## メソッド

| Method | 説明 |
| --- | --- |
| virtual void [Add](./add/)(const T\&) | コレクションに要素を追加します。 |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | コレクションの最初の要素（存在する場合）を指すイテレータを取得します。このイテレータは、[GetEnumerator()](../ienumerable/getenumerator/) が T のコピーオブジェクトを返すため、参照オブジェクトを変更するために使用できません。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | const 修飾されたコレクションインスタンスの最初の要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | コレクションの最初の const 修飾要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | コレクションの最後の const 修飾要素の直後を指すイテレータを取得します（存在する場合）。 |
| virtual void [Clear](./clear/)() | コレクションからすべての要素を削除します。 |
| virtual **bool** [Contains](./contains/)(const T\&) const | 要素がコレクションに存在するかチェックします。 |
| virtual void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | コレクションのすべての要素を既存の配列要素にコピーします。 |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | コレクションの最後の要素の直後を指すイテレータを取得します（存在する場合）。このイテレータは、[GetEnumerator()](../ienumerable/getenumerator/) が T のコピーオブジェクトを返すため、参照オブジェクトを変更するために使用できません。 |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | const 修飾されたコレクションインスタンスの最後の要素の直後を指すイテレータを取得します（存在する場合）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 では NaN はどの値とも等しくないと規定されていますが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 では NaN はどの値とも等しくないと規定されていますが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual int [get_Count](./get_count/)() const | コレクション内の要素数を取得します。 |
| virtual **bool** [get_IsReadOnly](./get_isreadonly/)() const | コレクションが読み取り専用かどうかをチェックします。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() const | コレクションが同期されているオブジェクトを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | 列挙子を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
|  [ICollection](./icollection/)() | デフォルトコンストラクタです。 |
|  [ICollection](./icollection/)(const [ICollection](./)\&) | コピーコンストラクタです。 |
|  [ICollection](./icollection/)([ICollection](./)\&&) | ムーブコンストラクタです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType に記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | シーケンスに対してアキュムレータ関数を適用します。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | シーケンスのすべての要素が条件を満たすかどうかを判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | シーケンスが要素を含むかどうかを判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | シーケンスに要素が存在するか、または条件を満たす要素があるかを判定します。 |
| T [LINQ_Average](../ienumerable/linq_average/)() | 数値シーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 入力シーケンスの各要素に変換関数を適用して得られる値のシーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 要素を指定された型にキャストします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 2 つのシーケンスを連結します。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | シーケンスが指定された値を含むかどうかを判定します。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | シーケンス内の要素数を返します（直接カウントで算出）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンス内の要素数を返します。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | シーケンスの指定インデックスにある要素を返します。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | シーケンスの指定インデックスにある要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)() | シーケンスの最初の要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの最初の要素を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | シーケンスの最初の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 条件を満たすシーケンスの最初の要素を返します。該当要素が見つからない場合はデフォルト値を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | シーケンスの要素をグループ化します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | シーケンスの要素をグループ化します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | シーケンスの最後の要素を返します。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | シーケンスの最後の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 汎用シーケンスの各要素に変換関数を適用し、最大の結果値を返します。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 汎用シーケンスの各要素に変換関数を適用し、最小の結果値を返します。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 指定された型に基づいてシーケンスの要素をフィルタリングします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector が選択したキー値に従って、シーケンスの要素を昇順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector が選択したキー値に従って、シーケンスの要素を降順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | シーケンスの要素順序を反転します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | シーケンスの要素を変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 要素のインデックスを取り入れて、シーケンスの各要素を新しい形に変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | シーケンスの各要素を投影し、結果のシーケンスを 1 つに結合します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素をスキップし、残りを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素を返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | シーケンスから配列を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | シーケンスから List<T> を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 指定された述語に基づいてシーケンスをフィルタリングします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [ICollection](./)\& [operator=](./operator_equal/)([ICollection](./)\&&) | ムーブ代入演算子です。 |
| [ICollection](./)\& [operator=](./operator_equal/)(const [ICollection](./)\&) | ムーブ代入演算子です。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| virtual **bool** [Remove](./remove/)(const T\&) | コレクションから要素を削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | 現在のコンテナの const begin イテレータの実装を取得します。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | 現在のコンテナの begin イテレータの実装を取得します。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | 現在のコンテナの const end イテレータの実装を取得します。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | 現在のコンテナの end イテレータの実装を取得します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~ICollection](./~icollection/)() | デストラクタです。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [ValueType](./valuetype/) | 値型の名前です。 |
| [ThisType](./thistype/) | コレクション型の名前です。 |

## 参照

* クラス [IEnumerable](../ienumerable/)
* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)