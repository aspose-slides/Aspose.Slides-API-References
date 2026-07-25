---
title: KeyedCollection
second_title: "Aspose.Slides for C++ API リファレンス"
description: "キーが埋め込まれた要素の抽象コレクションです。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てる必要があります。スタック上や operator new でこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡してください。"
type: docs
weight: 14
url: /ja/system.collections.objectmodel/keyedcollection/
---
## KeyedCollection クラス

埋め込みキーを持つ要素の抽象コレクションです。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。

```cpp
template<typename TKey,typename TItem>class KeyedCollection : public System::Collections::ObjectModel::Collection<TItem>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TKey | キーの型。 |
| TItem | 値の型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Add](./add/)(const TItem\&) override | コンテナの末尾に項目を追加します。 |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | コレクションの最初の要素（存在する場合）を指すイテレータを取得します。このイテレータは、[GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) が T のコピーオブジェクトを返すため、参照されたオブジェクトを変更するために使用できません。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | コレクションの const 修飾されたインスタンスの最初の要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | コレクションの最初の const 修飾要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | コレクションの最後の const 修飾要素（存在する場合）の直後を指すイテレータを取得します。 |
| void [Clear](../collection/clear/)() override | すべての要素を削除します。 |
| [Collection](../collection/collection/)() | 空のコレクションを作成します。 |
| [Collection](../collection/collection/)([SharedPtr](../../system/sharedptr/)\<[Generic::IList](../../system.collections.generic/ilist/)\<T\>\>) |  |
| **bool** [Contains](./contains/)(TKey) | キーがコンテナに存在するか確認します。 |
| **bool** [Contains](../collection/contains/)(const T\&) const override | 項目がコレクションに存在するか確認します。 |
| void [CopyTo](../collection/copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | コレクションの要素を既存の配列要素にコピーします。 |
| [const_reverse_iterator](../collection/const_reverse_iterator/) [crbegin](../collection/crbegin/)() const | コレクションの最後の const 修飾要素（逆順で最初）への逆イテレータを取得します。 |
| [const_reverse_iterator](../collection/const_reverse_iterator/) [crend](../collection/crend/)() const | コレクション開始前の存在しない const 修飾要素に対する逆イテレータを取得します。 |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | コレクションの最後の要素（存在する場合）の直後を指すイテレータを取得します。このイテレータは、[GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) が T のコピーオブジェクトを返すため、参照されたオブジェクトを変更するために使用できません。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | コレクションの const 修飾インスタンスの最後の要素（存在する場合）の直後を指すイテレータを取得します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<TKey\>\> [get_Comparer](./get_comparer/)() | 比較子を取得します。 |
| int [get_Count](../collection/get_count/)() const override | 要素数を取得します。 |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | コレクションが固定サイズかどうかを確認します。 |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | コレクションが読み取り専用かどうかを確認します。 |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IList](../../system.collections.generic/ilist/)\<T\>\> [get_Items](../collection/get_items/)() | 内部データ構造へのアクセサです。 |
| const [Generic::ListPtr](../../system.collections.generic/listptr/)\<T\> [get_Items](../collection/get_items/)() const | 内部データ構造へのアクセサです。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | コレクションが同期されているオブジェクトを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](../collection/getenumerator/)() override | コレクションを反復する列挙子を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドと同等です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しと同等です。 |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | デフォルトコンストラクタです。 |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | コピーコンストラクタです。 |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | ムーブコンストラクタです。 |
| TItem [idx_get](./idx_get/)(TKey) | 特定のインデックスの項目を取得します。 |
| T [idx_get](../collection/idx_get/)(int) const override | 指定されたインデックスの値を取得します。 |
| void [idx_set](../collection/idx_set/)(int, T) override | 指定されたインデックスに値を設定します。 |
| int [IndexOf](../collection/indexof/)(const T\&) const override | コレクション内の要素を検索します。 |
| void [Insert](../collection/insert/)(int, const T\&) override | 項目を指定された位置に挿入します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子と同等です。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | シーケンスに対して累積関数を適用します。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | シーケンスのすべての要素が条件を満たすかどうかを判定します。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | シーケンスに要素が含まれているかを判定します。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | シーケンスの任意の要素が存在するか、条件を満たすかを判定します。 |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 数値シーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 入力シーケンスの各要素に変換関数を適用して得られる値のシーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 要素を指定された型にキャストします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 2 つのシーケンスを連結します。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | シーケンスが指定された値を含むかどうかを判定します。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | シーケンスの要素数を返します（直接カウントによる）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの要素数を返します。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | シーケンスの指定インデックスの要素を返します。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | シーケンスの指定インデックスの要素を返します。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | シーケンスの最初の要素を返します。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの最初の要素を返します。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | シーケンスの最初の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 条件を満たすシーケンスの最初の要素を返します。該当要素がない場合はデフォルト値を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | シーケンスの要素をグループ化します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | シーケンスの要素をグループ化します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | シーケンスの最後の要素を返します。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | シーケンスの最後の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 汎用シーケンスの各要素に変換関数を適用し、最大の結果値を返します。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 汎用シーケンスの各要素に変換関数を適用し、最小の結果値を返します。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 指定された型に基づいてシーケンスの要素をフィルタリングします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector によって選択されたキー値に従って、シーケンスの要素を昇順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector によって選択されたキー値に従って、シーケンスの要素を降順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | シーケンスの要素の順序を反転します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | シーケンスの要素を変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 要素のインデックスを組み込んで、シーケンスの各要素を新しい形に変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | シーケンスの各要素を投影し、結果のシーケンスを 1 つのシーケンスに結合します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素をスキップし、残りを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素を返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | シーケンスから配列を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | シーケンスから List<T> を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 指定された述語に基づいてシーケンスをフィルタリングします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドと同等です。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | ムーブ代入演算子です。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | ムーブ代入演算子です。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| T\& [operator[]](../collection/operator[]/)(int) | 指定されたインデックスの値を取得します。 |
| const T\& [operator[]](../collection/operator[]/)(int) const | 指定されたインデックスの値を取得します。 |
| [reverse_iterator](../collection/reverse_iterator/) [rbegin](../collection/rbegin/)() | コレクションの最後の要素（逆順で最初）への逆イテレータを取得します。 |
| [const_reverse_iterator](../collection/const_reverse_iterator/) [rbegin](../collection/rbegin/)() const | const 修飾されたコレクションの最後の要素（逆順で最初）への逆イテレータを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| **bool** [Remove](./remove/)(TKey) | キーをコンテナから削除します。 |
| **bool** [Remove](../collection/remove/)(const T\&) override | 特定の項目を削除します。 |
| void [RemoveAt](../collection/removeat/)(int) override | 指定位置の項目を削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| [reverse_iterator](../collection/reverse_iterator/) [rend](../collection/rend/)() | コレクション開始前の存在しない要素に対する逆イテレータを取得します。 |
| [const_reverse_iterator](../collection/const_reverse_iterator/) [rend](../collection/rend/)() const | const 修飾されたコレクション開始前の存在しない要素に対する逆イテレータを取得します。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 特定のテンプレート引数を共有ポインタではなく弱ポインタとして扱うようにします（該当する場合）。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドと同等です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../collection/virtualizebeginconstiterator/)() const override | 現在のコンテナの const begin イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../collection/virtualizebeginiterator/)() override | 現在のコンテナの begin イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../collection/virtualizeendconstiterator/)() const override | 現在のコンテナの const end イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../collection/virtualizeenditerator/)() override | 現在のコンテナの end イテレータの実装を取得します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | デストラクタです。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [defaultThreshold](./defaultthreshold/) | ルックアップ辞書作成閾値（デフォルト）です。 |

## 参照

* クラス [Collection](../collection/)
* 名前空間 [System::Collections::ObjectModel](../)
* ライブラリ [Aspose.Slides](../../)