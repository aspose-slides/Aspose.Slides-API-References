---
title: List
second_title: C++ 用 Aspose.Slides API リファレンス
description: List の前方宣言です。
type: docs
weight: 430
url: /ja/system.collections.generic/list/
---
## List クラス

[List](./) 前方宣言。

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 要素の型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++ 固有です。 |
| void [Add](./add/)(const T\&) override | リストの末尾に要素を追加します。 |
| void [AddInitializer](./addinitializer/)(int, const T *) | リストに要素を追加します。イニシャライザの変換時に使用されます。 |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | コレクション（または自身）からすべての要素を現在のリストの末尾に追加します。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | このコレクションへの読み取り専用参照を取得します。 |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | コレクションの最初の要素へのイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | const 修飾されたコレクションの最初の要素へのイテレータを取得します。 |
| int [BinarySearch](./binarysearch/)(const T\&) const | ソート済みリストで項目を検索します。 |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | ソート済みリストで項目を検索します。 |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | ソート済みリストで項目を検索します。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | コレクションの const 修飾された最初の要素へのイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | コレクションの末端の後ろにある存在しない const 修飾要素へのイテレータを取得します。 |
| void [Clear](./clear/)() override | すべての要素を削除します。 |
| **bool** [Contains](./contains/)(const T\&) const override | リストに項目が存在するか確認します。 |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | 要素を別の型に変換したリストを作成します。 |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | リスト要素を既存の配列要素へコピーします。 |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | すべての要素を既存の配列要素へコピーします。 |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | 指定されたインデックスから開始し、要素を既存の配列要素へコピーします。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | コレクションの最後の const 修飾要素への逆イテレータを取得します（逆順の最初）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | コレクションの開始前にある存在しない const 修飾要素への逆イテレータを取得します。 |
| [vector_t](./vector_t/)\& [data](./data/)() | 基礎データ構造へのアクセス関数です。 |
| const [vector_t](./vector_t/)\& [data](./data/)() const | 基礎データ構造へのアクセス関数です。 |
| [iterator](../ienumerable/iterator/) [end](./end/)() | コレクションの末端の後ろにある存在しない要素へのイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | const 修飾されたコレクションの末端の後ろにある存在しない要素へのイテレータを取得します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | リストに特定の述語を満たす要素が存在するか確認します。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | 特定の述語を満たす要素を検索します。 |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | 特定の述語を満たす要素を検索します。 |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | 特定の述語を満たす要素を検索します。 |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | 特定の述語を満たす要素を検索します。 |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | 特定の述語を満たす要素を検索します。 |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | 特定の述語を満たす最後の要素を検索します。 |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | リスト内のすべての要素に対してアクションを適用します。 |
| int [get_Capacity](./get_capacity/)() const | 現在のリスト容量を取得します。 |
| int [get_Count](./get_count/)() const override | 現在のリストの要素数を取得します。 |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | コレクションが固定サイズかどうかを確認します。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | コレクションが読み取り専用かどうかを確認します。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | コレクションが同期されているオブジェクトを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | リスト要素を反復する列挙子を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| **ThisPtr** [GetRange](./getrange/)(int, int) | リストのスライスを作成します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
|  [ICollection](../icollection/icollection/)() | デフォルトコンストラクタです。 |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | コピーコンストラクタです。 |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | ムーブコンストラクタです。 |
| T [idx_get](./idx_get/)(int) const override | 特定の位置にある要素を取得します。 |
| void [idx_set](./idx_set/)(int, T) override | 特定の位置に要素を設定します。 |
| int [IndexOf](./indexof/)(const T\&) const override | 特定の項目の最初のインデックスを取得します。 |
| int [IndexOf](./indexof/)(const T\&, int) const | リスト内で特定の項目を検索します。 |
| void [Insert](./insert/)(int, const T\&) override | 指定された位置に項目を挿入します。 |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | 特定の位置にデータ範囲を挿入します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | 指定されたオブジェクトを検索し、リスト全体で最後に出現する位置のゼロベースインデックスを返します。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | 指定されたオブジェクトを検索し、[List](./) の最初の要素から指定インデックスまでの範囲で最後に出現する位置のゼロベースインデックスを返します。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | 指定されたオブジェクトを検索し、[List](./) の指定された要素数を含み、指定インデックスで終了する範囲で最後に出現する位置のゼロベースインデックスを返します。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | シーケンスに対してアキュムレータ関数を適用します。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | シーケンスのすべての要素が条件を満たすかどうかを判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | シーケンスに要素が存在するかどうかを判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | シーケンスの任意の要素が存在するか、条件を満たすかどうかを判定します。 |
| T [LINQ_Average](../ienumerable/linq_average/)() | 数値シーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 入力シーケンスの各要素に変換関数を適用して得られる値のシーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 要素を指定された型にキャストします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 2 つのシーケンスを連結します。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | シーケンスが指定された値を含むかどうかを判定します。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | シーケンスの要素数を返します（直接カウントによる計算）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの要素数を返します。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | シーケンスの指定インデックスにある要素を返します。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | シーケンスの指定インデックスにある要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)() | シーケンスの最初の要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの最初の要素を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | シーケンスの最初の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 条件を満たすシーケンスの最初の要素を返します。該当する要素がない場合はデフォルト値を返します。 |
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
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector が選択したキー値に基づき、シーケンスの要素を昇順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector が選択したキー値に基づき、シーケンスの要素を降順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | シーケンスの要素順序を反転させます。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | シーケンスの要素を変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 要素のインデックスを組み込んで、シーケンスの各要素を新しい形に変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | シーケンスの各要素を投影し、得られたシーケンスを1つに結合します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | シーケンスの開始から指定された数の連続要素をスキップし、残りを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | シーケンスの開始から指定された数の連続要素を返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | シーケンスから配列を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | シーケンスから List<T> を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 指定された述語に基づいてシーケンスをフィルタリングします。 |
|  [List](./list/)() | 空のリストを作成します。 |
|  [List](./list/)(int) | 事前定義された容量でリストを作成します。 |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | コピーコンストラクタです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン化を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | ムーブ代入演算子です。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | ムーブ代入演算子です。 |
| vector_t::reference [operator[]](./operator[]/)(int) | アクセサ関数です。 |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | アクセサ関数です。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | コレクションの最後の要素（逆順の最初）への逆イテレータを取得します。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | const 修飾されたコレクションの最後の要素（逆順の最初）への逆イテレータを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| **bool** [Remove](./remove/)(const T\&) override | リストから特定の項目の最初のインスタンスを削除します。 |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | 特定の述語に一致するすべての要素を削除します。 |
| void [RemoveAt](./removeat/)(int) override | 指定された位置の項目を削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [RemoveRange](./removerange/)(int, int) | リストのスライスを削除します。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | コレクションの開始前にある存在しない要素への逆イテレータを取得します。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | const 修飾されたコレクションの開始前にある存在しない要素への逆イテレータを取得します。 |
| void [Reverse](./reverse/)() | リスト全体の要素順序を逆転させます。 |
| void [Reverse](./reverse/)(int, int) | リストスライスの要素順序を逆転させます。 |
| void [set_Capacity](./set_capacity/)(int) | リストの容量を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | リスト内の要素をソートします。 |
| void [Sort](./sort/)() | デフォルト比較子を使用してリスト内の要素をソートします。 |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | リストスライス内の要素をソートします。 |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | リスト内の要素をソートします。 |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | リストを配列に変換します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| void [TrimExcess](./trimexcess/)() | リスト容量をサイズに合わせます。 |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | コレクションのすべての要素が指定された述語によって定義された条件に合致するかどうかを判定します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 現在のコンテナの begin const イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 現在のコンテナの begin イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 現在のコンテナの end const イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 現在のコンテナの end イテレータの実装を取得します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~ICollection](../icollection/~icollection/)() | デストラクタです。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [ValueType](./valuetype/) | この型です。 |
| [BaseType](./basetype/) | インターフェイス型です。 |
| [vector_t](./vector_t/) | 基礎データ型です。 |
| [iterator](./iterator/) | イテレータ型です。 |
| [const_iterator](./const_iterator/) | const イテレータ型です。 |
| [reverse_iterator](./reverse_iterator/) | 逆イテレータ型です。 |
| [const_reverse_iterator](./const_reverse_iterator/) | const 逆イテレータ型です。 |
| [IEnumerablePtr](./ienumerableptr/) | 同じ型の要素を保持するコンテナです。 |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** 型です。 |

## 注釈

[List](./) - 翻訳コードで使用される std::vector のラッパーです。要素型に対して operator == が実装されている必要があります。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // 最初のリストを作成します。
  auto list1 = MakeObject<List<int>>();

  // 最初のリストに要素を追加します。
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // 最初のリストをソートします。
  // 最初のリストの要素は次のようになります: {-5, 1, 3, 8}
  list1->Sort();

  // インデックス2の要素を削除します。
  // 最初のリストの要素は次のようになります: {-5, 1, 8}
  list1->RemoveAt(2);

  // インデックス1に要素を挿入します。
  // 最初のリストの要素は次のようになります: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // 2番目のリストを作成します。
  auto list2 = MakeObject<List<int>>();

  // 2番目のリストに要素を追加します。
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // 2番目のリストの要素を最初のリストに追加します。
  list1->AddRange(list2);

  // 最初のリストの要素を出力します。
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
このコード例は次の出力を生成します：
- 5 15 1 8 10 20 30
*/
```

## 参照

* クラス [Object](../../system/object/)
* クラス [IList](../ilist/)
* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)