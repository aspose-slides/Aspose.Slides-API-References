---
title: SortedDictionary
second_title: Aspose.Slides for C++ API リファレンス
description: ソート辞書型の前方宣言。
type: docs
weight: 521
url: /ja/system.collections.generic/sorteddictionary/
---
## SortedDictionary クラス

SortedDictionary 型の前方宣言。

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| TKey | キー型。 |
| TValue | 値型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | コンテナにキーと値のペアを追加します。 |
| virtual void [Add](../icollection/add/)(const T&) | コレクションに要素を追加します。 |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | コレクションの最初の要素（存在する場合）を指すイテレータを取得します。このイテレータは、[GetEnumerator()](../ienumerable/getenumerator/) が T のコピーオブジェクトを返すため、参照オブジェクトを変更するために使用できません。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | const 修飾されたコレクション インスタンスの最初の要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | コレクションの最初の const 修飾要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | コレクションの最後の const 修飾要素（存在する場合）の直後を指すイテレータを取得します。 |
| virtual void [Clear](../icollection/clear/)() | コレクション内のすべての要素を削除します。 |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | 要素がコレクションに存在するかチェックします。 |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | コンテナがキーを含むかチェックします。 |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | 辞書の内容を既存の配列要素にコピーします。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | コレクションの最後の const 修飾要素（逆順で最初）への逆イテレータを取得します。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | コレクションの開始前に存在しない const 修飾要素への逆イテレータを取得します。 |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | コレクションの最後の要素（存在する場合）の直後を指すイテレータを取得します。このイテレータは、[GetEnumerator()](../ienumerable/getenumerator/) が T のコピーオブジェクトを返すため、参照オブジェクトを変更するために使用できません。 |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | const 修飾されたコレクション インスタンスの最後の要素（存在する場合）の直後を指すイテレータを取得します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | IEC 60559:1989 により NaN は任意の値（NaN を含む）と等しくないとされているにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | IEC 60559:1989 により NaN は任意の値（NaN を含む）と等しくないとされているにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | 内部用途のみです。 |
| [SharedPtr](../../system/sharedptr/)<[System::Collections::Generic::IComparer](../icomparer/)<TKey>> [get_Comparer](./get_comparer/)() const | SortedDictionary<TKey,TValue> の要素の順序付けに使用される IComparer<TKey> を取得します。 |
| virtual int [get_Count](../icollection/get_count/)() const | コレクション内の要素数を取得します。 |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | コレクションのサイズが固定かどうかをチェックします。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | コレクションが読み取り専用かどうかをチェックします。 |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | コンテナがスレッドセーフかどうかをチェックします。 |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TKey>> [get_Keys](../idictionary/get_keys/)() const | キーコレクションにアクセスします。 |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | コレクションが同期されるオブジェクトを取得します。 |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TValue>> [get_Values](../idictionary/get_values/)() const | 値コレクションにアクセスします。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| static [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>> [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | シングルトンアクセサ関数です。 |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | 現在の辞書を反復する列挙子を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | 見つかった場合は値を返し、そうでない場合は **Value()** を返します。 |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | 見つかった場合は値を返し、そうでない場合は **defaultValue** を返します。 |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | 見つかった場合は値を返し、そうでない場合は **null** を返します（参照型にのみ意味があります）。 |
| [ICollection](../icollection/icollection/)() | デフォルトコンストラクタです。 |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | コピーコンストラクタです。 |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | ムーブコンストラクタです。 |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | 取得関数です。 |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | 設定関数です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | シーケンスに対してアキュムレータ関数を適用します。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | シーケンスのすべての要素が条件を満たすかどうかを判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | シーケンスに要素が含まれるかどうかを判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | シーケンスの任意の要素が存在するか、条件を満たすかどうかを判定します。 |
| T [LINQ_Average](../ienumerable/linq_average/)() | 数値シーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | 入力シーケンスの各要素に変換関数を適用して得られる値のシーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | 要素を指定された型にキャストします。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | 2 つのシーケンスを連結します。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | シーケンスが指定された値を含むかどうかを判定します。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | シーケンスの要素数を返します（直接カウントにより計算）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | 指定された条件を満たすシーケンスの要素数を返します。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | シーケンスの指定インデックスの要素を返します。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | シーケンスの指定インデックスの要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)() | シーケンスの最初の要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | 指定された条件を満たすシーケンスの最初の要素を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | シーケンスの最初の要素、またはシーケンスが空の場合はデフォルト値を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | 条件を満たすシーケンスの最初の要素、または見つからない場合はデフォルト値を返します。 |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | シーケンスの要素をグループ化します。 |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | シーケンスの要素をグループ化します。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | シーケンスの最後の要素を返します。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | シーケンスの最後の要素、またはシーケンスが空の場合はデフォルト値を返します。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | 汎用シーケンスの各要素に変換関数を適用し、最大の結果値を返します。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | 汎用シーケンスの各要素に変換関数を適用し、最小の結果値を返します。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | 指定された型に基づいてシーケンスの要素をフィルタリングします。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | keySelector が選択したキー値に従って、シーケンスの要素を昇順にソートします。 |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | keySelector が選択したキー値に従って、シーケンスの要素を降順にソートします。 |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | シーケンスの要素順序を反転します。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | シーケンスの要素を変換します。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | 要素のインデックスを組み込んで、シーケンスの各要素を新しい形に変換します。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>>>&) | シーケンスの各要素を投影し、結果のシーケンスを 1 つのシーケンスに結合します。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>>>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素をスキップし、残りを返します。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素を返します。 |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | シーケンスから配列を作成します。 |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | シーケンスから List<T> を作成します。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | 指定された述語に基づいてシーケンスをフィルタリングします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネル オブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | ムーブ代入演算子です。 |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | ムーブ代入演算子です。 |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | コレクションの最後の要素（逆順で最初）への逆イテレータを取得します。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | const 修飾されたコレクションの最後の要素（逆順で最初）への逆イテレータを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | nullptr と値型オブジェクトを参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | コンテナからキーを削除します。 |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | コレクションから要素を削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定値だけ減少させます。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | コレクションの開始前に存在しない要素への逆イテレータを取得します。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | const 修飾されたコレクションの開始前に存在しない要素への逆イテレータを取得します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタに設定します（shared の代わりに）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [SortedDictionary](./sorteddictionary/)() | 空の辞書を構築します。 |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>) | 空の辞書を構築します。 |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>) | コピーコンストラクタです。 |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>, const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>) | コピーコンストラクタです。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | 値を検索し、見つかった場合は取得します。 |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネル オブジェクトを使用してください。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | 現在のコンテナの begin const イテレータの実装を取得します。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | 現在のコンテナの begin イテレータの実装を取得します。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | 現在のコンテナの end const イテレータの実装を取得します。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | 現在のコンテナの end イテレータの実装を取得します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [~ICollection](../icollection/~icollection/)() | デストラクタです。 |
| virtual [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## typedefs

| Typedef | 説明 |
| --- | --- |
| [KeyCollection](./keycollection/) | キーコレクション型。 |
| [ValueCollection](./valuecollection/) | 値コレクション型。 |
| [map_t](./map_t/) | 基礎データ型。 |
| [this_t](./this_t/) | 自己型。 |
| [Ptr](./ptr/) | ポインタ型。 |
| [KVPair](./kvpair/) | キーと値のペア型。 |
| [IEnumerablePtr](./ienumerableptr/) | 同一要素のコレクション。 |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** 型。 |
| [iterator](./iterator/) | イテレータ型。 |
| [const_iterator](./const_iterator/) | const イテレータ型。 |
| [reverse_iterator](./reverse_iterator/) | リバースイテレータ型。 |
| [const_reverse_iterator](./const_reverse_iterator/) | const リバースイテレータ型。 |

## 備考

STL map をラップしたソート辞書クラスです。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうするとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡すようにしてください。

## 関連項目

* クラス [BaseDictionary](../basedictionary/)
* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)