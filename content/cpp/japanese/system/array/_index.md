---
title: Array
second_title: Aspose.Slides for C++ API リファレンス
description: "配列データ構造を表すクラスです。このクラスのオブジェクトは、System::MakeArray() および System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使ってインスタンスを作成しないでください。そうすると実行時エラーやアサーションフォルトが発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 14
url: /ja/system/array/
---
## 配列クラス

配列データ構造を表すクラスです。 このクラスのオブジェクトは [System::MakeArray()](../makearray/) と [System::MakeObject()](../makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション失敗が発生します。 常にこのクラスを [System::SmartPtr](../smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 配列の要素の型 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Add](./add/)(const T\&) override | このオブジェクトが表す配列は読み取り専用であるため、サポートされていません。 |
|  [Array](./array/)() | 空の配列を構築します。 |
|  [Array](./array/)(int, const T\&) | 要素を埋めるコンストラクタです。 |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | 要素を埋めるコンストラクタです。 |
|  [Array](./array/)(int, const T) | 要素を埋めるコンストラクタです。 |
|  [Array](./array/)(**vector_t**\&&) | ムーブコンストラクタです。 |
|  [Array](./array/)(const **vector_t**\&) | コピーコンストラクタです。 |
|  [Array](./array/)(const std::vector\<Q\>\&) | [Array](./) オブジェクトを構築し、**T** と同じ型だが **UnderlyingType** とは異なる型の値を持つ std::vector オブジェクトからコピーした値で埋めます。 |
|  [Array](./array/)(std::vector\<Q\>\&&) | [Array](./) オブジェクトを構築し、**T** と同じ型だが **UnderlyingType** とは異なる型の値を持つ std::vector オブジェクトからムーブした値で埋めます。 |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | [Array](./) オブジェクトを構築し、**UnderlyingType** 型の要素を含む指定された initializer list から値で埋めます。 |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | [Array](./) オブジェクトを構築し、**UnderlyingType** 型の要素を含む指定された配列から値で埋めます。 |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | [Array](./) オブジェクトを構築し、bool 型の要素を含む指定された initializer list から値で埋めます。 |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | 配列を読み取り専用コレクションにキャストします。 |
| [iterator](./iterator/) [begin](./begin/)() | コンテナの最初の要素へのイテレータを返します。コンテナが空の場合、返されるイテレータは [end()](./end/) と等しくなります。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | const 修飾されたコンテナの最初の要素へのイテレータを返します。コンテナが空の場合、返されるイテレータは [end()](./end/) と等しくなります。 |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | ソート済み配列で二分探索を実行します。 |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | 未実装です。 |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | コンテナの最初の const 修飾要素へのイテレータを返します。コンテナが空の場合、返されるイテレータは [cend()](./cend/) と等しくなります。 |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | コンテナの最後の要素の次の要素へのイテレータを返します。この要素はプレースホルダーとして機能し、アクセスしようとすると未定義動作になります。 |
| void [Clear](./clear/)() override | このオブジェクトが表す配列は読み取り専用であるため、サポートされていません。 |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 指定された配列の **startIndex** インデックスから **count** 個の値をデフォルト値で置き換えます。 |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | 配列をクローンします。 |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 指定されたソースから開始する [System.Array](./) の要素範囲をコピーします。 |
| **bool** [Contains](./contains/)(const T\&) const override | 指定された項目が配列に含まれているかどうかを判定します。 |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | 新しい [Array](./) オブジェクトを構築し、指定されたコンバータデリゲートを使用して **OutputType** 型に変換された指定配列の要素で埋めます。 |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | 新しい [Array](./) オブジェクトを構築し、指定されたコンバータ関数オブジェクトを使用して **OutputType** 型に変換された指定配列の要素で埋めます。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 指定された数の要素をソース配列からデスティネーション配列へコピーします。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 指定された数の要素をソース配列ビューからデスティネーション配列へコピーします。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | 指定された数の要素をソース配列からデスティネーション配列ビューへコピーします。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | 指定された数の要素をソース配列ビューからデスティネーション配列ビューへコピーします。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | スタック上のソース配列からデスティネーション配列へ指定された数の要素をコピーします。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | ソース配列からスタック上のデスティネーション配列へ指定された数の要素をコピーします。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | スタック上のソース配列からスタック上のデスティネーション配列へ指定された数の要素をコピーします。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | ソース配列の指定インデックスから開始し、指定された数の要素をデスティネーション配列の指定位置へコピーします。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | ソース配列ビューの指定インデックスから開始し、指定された数の要素をデスティネーション配列の指定位置へコピーします。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | ソース配列の指定インデックスから開始し、指定された数の要素をデスティネーション配列ビューの指定位置へコピーします。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | ソース配列ビューの指定インデックスから開始し、指定された数の要素をデスティネーション配列ビューの指定位置へコピーします。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | スタック上のソース配列の指定インデックスから開始し、指定された数の要素をデスティネーション配列の指定位置へコピーします。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | ソース配列の指定インデックスから開始し、指定された数の要素をスタック上のデスティネーション配列の指定位置へコピーします。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | スタック上のソース配列の指定インデックスから開始し、指定された数の要素をスタック上のデスティネーション配列の指定位置へコピーします。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | ソース配列ビューの指定インデックスから開始し、指定された数の要素をスタック上のデスティネーション配列の指定位置へコピーします。 |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | 現在の配列のすべての要素を指定されたデスティネーション配列にコピーします。要素は arrayIndex 引数で指定されたインデックスからデスティネーション配列に挿入されます。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | 現在の配列のすべての要素を指定されたデスティネーション配列にコピーします。要素は dstIndex 引数で指定されたインデックスからデスティネーション配列に挿入されます。 |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | 現在の配列のすべての要素を指定されたデスティネーション配列ビューにコピーします。要素は dstIndex 引数で指定されたインデックスからデスティネーション配列ビューに挿入されます。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | 現在の配列の指定された位置から開始し、指定された数の要素を指定されたデスティネーション配列にコピーします。要素は dstIndex 引数で指定されたインデックスからデスティネーション配列に挿入されます。 |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | 現在の配列の指定された位置から開始し、指定された数の要素を指定されたデスティネーション配列ビューにコピーします。要素は dstIndex 引数で指定されたインデックスからデスティネーション配列ビューに挿入されます。 |
| int [Count](./count/)() const | 配列のすべての次元における要素総数を表す数値を返します。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 逆順コンテナの最初の要素へのリバースイテレータを返します。これは非逆順コンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは [crend()](./crend/) と等しくなります。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 逆順コンテナの最後の要素の次の要素へのリバースイテレータを返します。これは非逆順コンテナの最初の要素の前の要素に対応します。この要素はプレースホルダーとして機能し、アクセスしようとすると未定義動作になります。 |
| **vector_t**\& [data](./data/)() | 配列要素の格納に使用される内部データ構造への参照を返します。 |
| const **vector_t**\& [data](./data/)() const | 配列要素の格納に使用される内部データ構造への定数参照を返します。 |
| vector_t::pointer [data_ptr](./data_ptr/)() | 配列要素が格納されているメモリバッファの先頭への生ポインタを返します。 |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | 配列要素が格納されているメモリバッファの先頭への定数生ポインタを返します。 |
| [iterator](./iterator/) [end](./end/)() | コンテナの最後の要素の次の要素へのイテレータを返します。この要素はプレースホルダーとして機能し、アクセスしようとすると未定義動作になります。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | const 修飾されたコンテナの最後の要素の次の要素へのイテレータを返します。この要素はプレースホルダーとして機能し、アクセスしようとすると未定義動作になります。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# の [Object.Equals](../object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値（NaNを含む）とも等しくないにもかかわらず、2つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | 指定された [Array](./) オブジェクトが、指定された述語の要件を満たす要素を含んでいるかどうかを判定します。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 指定された配列の中で、指定された述語の条件を満たす最初の要素を検索します。 |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 指定された述語で定義された条件に一致するすべての要素を取得します。 |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 指定された配列の中で、指定された述語の条件を満たす最初の要素を検索します。 |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | 指定された配列の各要素に対して、指定されたアクションを実行します。 |
| int [get_Count](./get_count/)() const override | 配列のサイズを返します。 |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | コレクションが固定サイズかどうかを確認します。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | 配列が読み取り専用かどうかを示します。 |
| **int32_t** [get_Length](./get_length/)() const override | 配列のすべての次元における全要素数を表す 32 ビット整数を返します。 |
| **int64_t** [get_LongLength](./get_longlength/)() const | 配列のすべての次元における全要素数を表す 64 ビット整数を返します。 |
| **int32_t** [get_Rank](./get_rank/)() const | 未実装です。 |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | コレクションが同期されているオブジェクトを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | 現在のオブジェクトが表す配列の要素に IEnumerator インターフェイスを提供する **Enumerator** オブジェクトへのポインタを返します。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# の [Object.GetHashCode()](../object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| int [GetLength](./getlength/)(int) | 指定された次元の要素数を返します。 |
| **int64_t** [GetLongLength](./getlonglength/)(int) | 指定された次元の要素数を 64 ビット整数として返します。 |
| int [GetLowerBound](./getlowerbound/)(int) const | 指定された次元の下限を返します。 |
| size_t [GetSizeTLength](./getsizetlength/)() const | 配列のすべての次元における全要素数を表す std::size_t 変数を返します。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../object/gettype/) 呼び出しのアナログです。 |
| int [GetUpperBound](./getupperbound/)(int) | 指定された次元の上限を返します。 |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | デフォルトコンストラクタです。 |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | コピーコンストラクタです。 |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | ムーブコンストラクタです。 |
| T [idx_get](./idx_get/)(int) const override | 指定されたインデックスのアイテムを返します。 |
| void [idx_set](./idx_set/)(int, T) override | 指定されたインデックスの配列要素に指定された値を設定します。 |
| int [IndexOf](./indexof/)(const T\&) const override | 配列内で指定されたアイテムが最初に出現するインデックスを決定します。 |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | 配列内で指定されたアイテムが最初に出現するインデックスを決定します。 |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | 指定されたインデックスから開始して、配列内で指定されたアイテムが最初に出現するインデックスを決定します。 |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | 開始インデックスと範囲内要素数で指定された配列の範囲内で、指定されたアイテムが最初に出現するインデックスを決定します。 |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | 現在のオブジェクトが表す配列を、指定された配列の値で埋めます。 |
| void [Initialize](./initialize/)() | 配列を **T** 型のデフォルト構築オブジェクトで埋めます。 |
| void [Insert](./insert/)(int, const T\&) override | 現在のオブジェクトが表す配列が読み取り専用であるためサポートされていません。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | 開始インデックスと範囲内要素数で指定された配列の範囲内で、指定されたアイテムが最後に出現するインデックスを決定します。 |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | 指定されたインデックスから開始して、配列内で指定されたアイテムが最後に出現するインデックスを決定します。 |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | 配列内で指定されたアイテムが最後に出現するインデックスを決定します。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | シーケンスに対してアキュムレータ関数を適用します。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | シーケンスのすべての要素が条件を満たすかどうかを判定します。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | シーケンスに要素が含まれるかどうかを判定します。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | シーケンスに要素が存在するか、または条件を満たすかどうかを判定します。 |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 数値シーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | 入力シーケンスの各要素に変換関数を適用して得られる値のシーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 要素を指定された型にキャストします。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 2 つのシーケンスを連結します。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | シーケンスに指定された値が含まれるかどうかを判定します。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | シーケンスの要素数を返します（直接カウントにより計算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの要素数を返します。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | シーケンスの指定インデックスにある要素を返します。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | シーケンスの指定インデックスにある要素を返します。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | シーケンスの最初の要素を返します。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの最初の要素を返します。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | シーケンスの最初の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 条件を満たすシーケンスの最初の要素を返します。該当する要素が見つからない場合はデフォルト値を返します。 |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | シーケンスの要素をグループ化します。 |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | シーケンスの要素をグループ化します。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | シーケンスの最後の要素を返します。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | シーケンスの最後の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | 汎用シーケンスの各要素に変換関数を適用し、最大の結果値を返します。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | 汎用シーケンスの各要素に変換関数を適用し、最小の結果値を返します。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 指定された型に基づいてシーケンスの要素をフィルタリングします。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | keySelector が選択したキー値に従って、シーケンスの要素を昇順にソートします。 |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | keySelector が選択したキー値に従って、シーケンスの要素を降順にソートします。 |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | シーケンスの要素の順序を逆にします。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | シーケンスの要素を変換します。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | 要素のインデックスを取り入れて、シーケンスの各要素を新しい形に変換します。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | シーケンスの各要素を投影し、結果のシーケンスを 1 つのシーケンスに結合します。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素をスキップし、残りを返します。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素を返します。 |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | シーケンスから配列を作成します。 |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | シーケンスから List<T> を作成します。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 指定された述語に基づいてシーケンスをフィルタリングします。 |
| void [Lock](../object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../lockcontext/) セントリーオブジェクトを使用してください。 |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | [operator<()](../operator_less/) を用いて要素を比較し、配列の最大要素を見つけます。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | [operator<()](../operator_less/) を用いて要素を比較し、配列の最小要素を見つけます。 |
|  [Object](../object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | ムーブ代入演算子です。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | ムーブ代入演算子です。 |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | 指定されたインデックスのアイテムを返します。 |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | 指定されたインデックスのアイテムを返します。 |
| void * [raw_data_ptr](./raw_data_ptr/)() override | 単一次元配列の最初の要素へのポインタを返します。多次元配列の場合、結果は未定義です。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 逆順コンテナの最初の要素へのリバースイテレータを返します。これは逆順でないコンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは [rend()](./rend/) と等価です。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 逆コンテナの最初の要素へのリバースイテレータを返します。非逆コンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは [rend()](./rend/) と等しくなります。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトをnullptrと参照で比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) の文字列とnullptrの場合の特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) の文字列の場合の特殊化です。 |
| **bool** [Remove](./remove/)(const T\&) override | 現在のオブジェクトが表す配列が読み取り専用であるため、サポートされていません。 |
| void [RemoveAt](./removeat/)(int) override | 現在のオブジェクトが表す配列が読み取り専用であるため、サポートされていません。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 逆コンテナの最後の要素の次の要素へのリバースイテレータを返します。非逆コンテナの最初の要素の前の要素に対応します。この要素はプレースホルダであり、アクセスしようとすると未定義の動作になります。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 逆コンテナの最後の要素の次の要素へのリバースイテレータを返します。非逆コンテナの最初の要素の前の要素に対応します。この要素はプレースホルダであり、アクセスしようとすると未定義の動作になります。 |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | 指定された配列のサイズを指定された値に変更するか、指定サイズの新しい配列を作成します。 |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | 指定された配列の要素を逆順にします。 |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 指定された配列の要素範囲を逆順にします。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 配列が格納されたポインタを弱参照として扱うようにします（該当する場合）。 |
| void [SetValue](./setvalue/)(const T\&, int) | 指定されたインデックスの要素の値を設定します。 |
| int [SharedCount](../object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | デフォルトの比較器を使用して、指定された配列の要素をソートします。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | デフォルトの比較器を使用して、指定された配列の要素範囲をソートします。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | 指定された比較器を使用して、指定された配列の要素をソートします。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | 実装されていません。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | 指定された比較を使用して、指定された配列の要素をソートします。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | キーを含む配列と対応する項目の配列の 2 つの配列を、キー配列の値に基づいてソートします。要素は operator< で比較されます。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | キーを含む配列と対応する項目の配列の 2 つの配列を、キー配列の値に基づいてソートします。要素はデフォルトの比較器で比較されます。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# の [Object.ToString()](../object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 指定された配列のすべての要素が、指定された述語で定義された条件を満たすかどうかを判定します。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# の typeof([System.Object](../object/)) 構文を実装します。 |
| void [Unlock](../object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../lockcontext/) セントリーオブジェクトを使用してください。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 現在のコンテナの const begin イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 現在のコンテナの begin イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 現在のコンテナの const end イテレータの実装を取得します。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 現在のコンテナの end イテレータの実装を取得します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | デストラクタ。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破壊します。すべての内部データ構造を解放します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [ValueType](./valuetype/) | 配列の要素の型のエイリアスです。 |
| [UnderlyingType](./underlyingtype/) | 配列の各要素を表すのに使用される型のエイリアスです。 |
| [EnumerablePtr](./enumerableptr/) | **T** 型の要素を含む IEnumerable オブジェクトを指す共有ポインタ型のエイリアスです。 |
| [EnumeratorPtr](./enumeratorptr/) | **T** 型の要素を含む IEnumerator オブジェクトを指す共有ポインタ型のエイリアスです。 |
| [iterator](./iterator/) | イテレータ型です。 |
| [const_iterator](./const_iterator/) | const イテレータ型です。 |
| [reverse_iterator](./reverse_iterator/) | リバースイテレータ型です。 |
| [const_reverse_iterator](./const_reverse_iterator/) | const リバースイテレータ型です。 |

## 備考

```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // 配列を作成し、要素を埋めます。
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // 配列の要素を出力します。
  Print(arrayPtr);

  // 配列の要素を昇順でソートします。
  Array<int32_t>::Sort(arrayPtr);

  // 配列の要素を出力します。
  Print(arrayPtr);

  // 配列の要素数を出力します。
  std::cout << arrayPtr->get_Length() << std::endl;

  // 値が 4 の要素のインデックスを出力します。
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // 配列のサイズを変更します。
  Array<int32_t>::Resize(arrayPtr, 3);

  // 配列の要素を出力します。
  Print(arrayPtr);

  return 0;
}
/*
このコード例は以下の出力を生成します。
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## 参照

* クラス [ArrayBase](../arraybase/)
* クラス [IList](../../system.collections.generic/ilist/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)