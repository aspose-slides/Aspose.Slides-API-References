---
title: _ValueList
second_title: Aspose.Slides for C++ APIリファレンス
description: "辞書の値のリストを実装します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず System::SmartPtr ポインタでラップし、そのポインタを関数に引数として渡してください。"
type: docs
weight: 40
url: /ja/system.collections.generic/_valuelist/
---
## _ValueList クラス

辞書の値のリストを実装します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。

```cpp
template<typename Dict>class _ValueList : public System::Collections::Generic::_ValueCollection<Dict>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [_ValueCollection](../_valuecollection/_valuecollection/)(const typename Dict::Ptr\&) | 指定された辞書を参照するコレクションを初期化します。 |
|  [_ValueList](./_valuelist/)(const typename Dict::Ptr\&) | 指定された辞書を参照するコレクションを初期化します。 |
| void [Add](../ikvcollection/add/)(const T\&) override | アイテムをコンテナに追加します。 |
|  [BaseKVCollection](../basekvcollection/basekvcollection/)(const typename Dict::Ptr\&) | コレクションを作成します。 |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | コレクションの最初の要素（存在する場合）を指すイテレータを取得します。このイテレータは [GetEnumerator()](../ienumerable/getenumerator/) が T のコピーオブジェクトを返すため、参照オブジェクトの変更には使用できません。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | const 修飾されたコレクションインスタンスの最初の要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | コレクションの最初の const 修飾要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | コレクションの最後の const 修飾要素の直後を指すイテレータを取得します。 |
| void [Clear](../ikvcollection/clear/)() override | コンテナ内のすべての要素を削除します。 |
| **bool** [Contains](../_valuecollection/contains/)(const [TValue](../_valuecollection/tvalue/)\&) const override | アイテムがコンテナに存在するか確認します。 |
| void [CopyTo](../basekvcollection/copyto/)([ArrayPtr](../../system/arrayptr/)\<KV\>, int) override | 既存の配列要素にデータをコピーします。 |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | コレクションの最後の要素（存在する場合）直後を指すイテレータを取得します。このイテレータは [GetEnumerator()](../ienumerable/getenumerator/) が T のコピーオブジェクトを返すため、参照オブジェクトの変更には使用できません。 |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | const 修飾されたコレクションインスタンスの最後の要素（存在する場合）直後を指すイテレータを取得します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 では NaN はどの値とも等しくありませんが、C# スタイルの比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 では NaN はどの値とも等しくありませんが、C# スタイルの比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| int [get_Count](../basekvcollection/get_count/)() const override | 要素数を取得します。 |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | コレクションが固定サイズかどうかを確認します。 |
| **bool** [get_IsReadOnly](../ikvcollection/get_isreadonly/)() const override | コンテナが読み取り専用かどうかを確認します。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | コレクションが同期されているオブジェクトを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[TValue](../_valuecollection/tvalue/)\>\> [GetEnumerator](../_valuecollection/getenumerator/)() override | 値を列挙するイテレータを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
|  [ICollection](../icollection/icollection/)() | デフォルトコンストラクタ。 |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | コピーコンストラクタ。 |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | ムーブコンストラクタ。 |
| virtual [TValue](../_valuecollection/tvalue/) [idx_get](./idx_get/)(int) const | 指定された位置の値を取得します。 |
| void [idx_set](../ikvcollection/idx_set/)(int, T) override | セッタ関数。 |
| int [IndexOf](../ikvcollection/indexof/)(const T\&) const override | コンテナ内のアイテムのインデックスを取得します。 |
| void [Insert](../ikvcollection/insert/)(int, const T\&) override | 指定された位置にアイテムを挿入します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | シーケンス全体に集約関数を適用します。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | シーケンスのすべての要素が条件を満たすか判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | シーケンスに要素が含まれるか判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | シーケンス内に条件を満たす要素が存在するか判定します。 |
| T [LINQ_Average](../ienumerable/linq_average/)() | 数値シーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 入力シーケンスの各要素に変換関数を適用し、その結果の平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 要素を指定された型にキャストします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 2 つのシーケンスを連結します。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | シーケンスが指定された値を含むか判定します。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | 直接カウントによって算出されたシーケンスの要素数を返します。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 条件を満たすシーケンス要素の数を返します。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | シーケンスの指定インデックスにある要素を返します。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | シーケンスの指定インデックスにある要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)() | シーケンスの最初の要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 条件を満たすシーケンスの最初の要素を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | シーケンスが空の場合はデフォルト値を返し、そうでなければ最初の要素を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 条件を満たすシーケンスの最初の要素を返します。該当要素が無い場合はデフォルト値を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | シーケンスの要素をグループ化します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | シーケンスの要素をグループ化します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | シーケンスの最後の要素を返します。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | シーケンスが空の場合はデフォルト値を返し、そうでなければ最後の要素を返します。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ジェネリックシーケンスの各要素に変換関数を適用し、最大の結果値を返します。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ジェネリックシーケンスの各要素に変換関数を適用し、最小の結果値を返します。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 指定された型に基づいてシーケンスの要素をフィルタリングします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | キーセレクタで選択されたキー値に従い、シーケンスの要素を昇順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | キーセレクタで選択されたキー値に従い、シーケンスの要素を降順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | シーケンス内の要素の順序を逆転させます。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | シーケンスの要素を変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 要素のインデックスを組み込んで、各要素を新しい形に変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | 各要素を投影し、得られたシーケンスを 1 つのシーケンスに結合します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素をスキップし、残りを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素を返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | シーケンスから配列を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | シーケンスから List<T> を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 指定された述語でシーケンスをフィルタリングします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローンを可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | ムーブ代入演算子。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | ムーブ代入演算子。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [Remove](../ikvcollection/remove/)(const T\&) override | コンテナからアイテムを削除します。 |
| void [RemoveAt](../ikvcollection/removeat/)(int) override | 指定された位置のアイテムを削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [SetTemplateWeakPtr](../basekvcollection/settemplateweakptr/)(**uint32_t**) override | コンパイルを可能にしますが、この構造体はデータを所有しないため実際には何もしません。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントしその値を返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のアンロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeBeginConstIterator](../_valuecollection/virtualizebeginconstiterator/)() const override | 現在のコンテナに対する const begin イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeBeginIterator](../_valuecollection/virtualizebeginiterator/)() override | 現在のコンテナに対する begin イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeEndConstIterator](../_valuecollection/virtualizeendconstiterator/)() const override | 現在のコンテナに対する const end イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeEndIterator](../_valuecollection/virtualizeenditerator/)() override | 現在のコンテナに対する end イテレータの実装を取得します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~ICollection](../icollection/~icollection/)() | デストラクタ。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [TValue](./tvalue/) | 値の型。 |

## 参照

* クラス [_ValueCollection](../_valuecollection/)
* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)