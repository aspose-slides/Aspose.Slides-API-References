---
title: LinkedList
second_title: Aspose.Slides for C++ API リファレンス
description: LinkedList の前方宣言。
type: docs
weight: 404
url: /ja/system.collections.generic/linkedlist/
---
## LinkedList クラス

[LinkedList](./) 前方宣言。

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 含まれる値の型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Add](./add/)(const T\&) override | リストの末尾に **element** を追加します。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | リストの **node** の後に **element** を追加します。 |
| void [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | リストの **node** の後に **newNode** を追加します。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | リストの **node** の前に **element** を追加します。 |
| void [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | リストの **node** の前に **newNode** を追加します。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddFirst](./addfirst/)(const T\&) | リストの先頭に **element** を追加します。 |
| void [AddFirst](./addfirst/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | リストの先頭に **newNode** を追加します。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddLast](./addlast/)(const T\&) | リストの末尾に **element** を追加します。 |
| void [AddLast](./addlast/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | リストの末尾に **newNode** を追加します。 |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | コレクションの最初の要素へのイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | const 修飾されたコレクションの最初の要素へのイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | コレクションの最初の const 修飾要素へのイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | コレクションの末尾の外側にある存在しない const 修飾要素へのイテレータを取得します。 |
| void [Clear](./clear/)() override | リスト内のすべての要素を削除します。 |
| **bool** [Contains](./contains/)(const T\&) const override | **element** がリストに存在するか確認します。 |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | コンテナのデータを既存の配列要素にコピーします。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | コレクションの最後の const 修飾要素（逆順では最初）への逆イテレータを取得します。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | コレクションの先頭の前にある存在しない const 修飾要素への逆イテレータを取得します。 |
| [iterator](../ienumerable/iterator/) [end](./end/)() | コレクションの末尾の外側にある存在しない要素へのイテレータを取得します。 |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | const 修飾されたコレクションの末尾の外側にある存在しない要素へのイテレータを取得します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN が等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN が等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [Find](./find/)(const T\&) const | リスト内で **element** を前方向に検索します。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [FindLast](./findlast/)(const T\&) const | リスト内で **element** を逆方向に検索します。 |
| int [get_Count](./get_count/)() const override | リストの要素数を取得します。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_First](./get_first/)() const | リストの最初の要素へのポインタを取得します。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | コレクションが読み取り専用か確認します。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_Last](./get_last/)() const | リストの最後の要素へのポインタを取得します。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | コレクションが同期されているオブジェクトを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() override | 現在の [LinkedList](./) を反復処理する列挙子を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
|  [ICollection](../icollection/icollection/)() | デフォルトコンストラクタ。 |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | コピーコンストラクタ。 |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | ムーブコンストラクタ。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるか確認します。C# の 'is' 演算子のアナログです。 |
|  [LinkedList](./linkedlist/)() | 空の [LinkedList](./) を作成します。 |
|  [LinkedList](./linkedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>\&) | コピーコンストラクタ。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | シーケンス上で累積関数を適用します。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | シーケンスのすべての要素が条件を満たすか判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | シーケンスに要素が含まれるか判定します。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | シーケンスに要素が存在するか、条件を満たすか判定します。 |
| T [LINQ_Average](../ienumerable/linq_average/)() | 数値シーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 入力シーケンスの各要素に変換関数を適用して得られる値の平均を計算します。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 要素を指定された型にキャストします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 2 つのシーケンスを連結します。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | シーケンスが指定された値を含むか判定します。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | シーケンスの要素数を返します（直接カウントによる）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの要素数を返します。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | シーケンスの指定インデックスの要素を返します。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | シーケンスの指定インデックスの要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)() | シーケンスの最初の要素を返します。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの最初の要素を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | シーケンスの最初の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 条件を満たすシーケンスの最初の要素を返します。見つからない場合はデフォルト値を返します。 |
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
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | シーケンスの要素の順序を反転します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | シーケンスの要素を変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 要素のインデックスを組み込んで、シーケンスの各要素を新しい形に変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | シーケンスの各要素を投影し、得られたシーケンスを 1 つに結合します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素をスキップし、残りを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素を返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | シーケンスから配列を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | シーケンスから List<T> を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 指定された述語に基づいてシーケンスをフィルタリングします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | ムーブ代入演算子。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | ムーブ代入演算子。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | コレクションの最後の要素（逆順では最初）への逆イテレータを取得します。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | const 修飾コレクションの最後の要素（逆順では最初）への逆イテレータを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| **bool** [Remove](./remove/)(const T\&) override | リストから指定された **element** の最初の出現を削除します。 |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | リストからノードを削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [RemoveFirst](./removefirst/)() | リストの最初のノードを削除します。 |
| void [RemoveLast](./removelast/)() | リストの最後のノードを削除します。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | コレクションの先頭の前にある存在しない要素への逆イテレータを取得します。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | const 修飾コレクションの先頭の前にある存在しない要素への逆イテレータを取得します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 現在のコンテナの begin const イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 現在のコンテナの begin イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 現在のコンテナの end const イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 現在のコンテナの end イテレータの実装を取得します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~ICollection](../icollection/~icollection/)() | デストラクタ。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 型定義

| 型エイリアス | 説明 |
| --- | --- |
| [list_t](./list_t/) | 基底データ型。 |
| [iterator](./iterator/) | イテレータ型。 |
| [const_iterator](./const_iterator/) | const イテレータ型。 |
| [reverse_iterator](./reverse_iterator/) | 逆イテレータ型。 |
| [const_reverse_iterator](./const_reverse_iterator/) | const 逆イテレータ型。 |

## 備考

リンクドリスト コンテナ。std::list のラッパーを実装しています。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡すようにしてください。

```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // LinkedList クラスのインスタンスを作成します。
  auto list = MakeObject<LinkedList<int>>();

  // リンクドリストに要素を追加します。
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // リンクドリストの項目を出力します。
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
このコード例は次の出力を生成します:
1 15 25 30
*/
```

## 参照

* クラス [Object](../../system/object/)
* クラス [ICollection](../icollection/)
* クラス [Invalidatable](../../system.collections/invalidatable/)
* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)