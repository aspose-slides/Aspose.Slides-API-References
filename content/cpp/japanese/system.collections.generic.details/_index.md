---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 352
url: /ja/system.collections.generic.details/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | IEnumerable.Cast() と IEnumerable.OfType() の拡張メソッドで使用される Enumerable。 |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | IEnumerable.Select() の拡張メソッドで使用される Enumerable。 |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | IEnumerable.Cast() の拡張メソッドで使用される Enumerator。 |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | IEnumerable.OfType() の拡張メソッドで使用される Enumerator。 |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | IEnumerable.Select() の拡張メソッドで使用される Enumerator。 |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## 構造体

| 構造体 | 説明 |
| --- | --- |
| [ComparerType](./comparertype/) | 要素を 'less' セマンティクスで比較します。 |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | 要素を 'less' セマンティクスで比較します。 |
| [has_method_compareto](./has_method_compareto/) | 指定された型に CompareTo メソッドが存在するか確認します。存在する場合は std::true_type を継承し、存在しない場合は std::false_type を継承します。std::enable_if で使用できます。 |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | 指定された型に CompareTo(SharedPtr<T>) メソッドが存在するか確認します。存在する場合は std::true_type を継承し、存在しない場合は std::false_type を継承します。std::enable_if で使用できます。 |
| [IsEqualExist](./isequalexist/) | 型が operator == を提供しているか確認します。 |
## 関数

| 関数 | 説明 |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | インデックスがコンテナの境界外かどうかを確認します（コンテナサイズは除外）。 |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | インデックスがコンテナの境界外かどうかを確認します（コンテナサイズは除外）。 |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | インデックスがコンテナの境界外かどうかを確認します（コンテナサイズを含む）。 |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | インデックスがコンテナの境界外かどうかを確認します（コンテナサイズを含む）。 |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | 特定のクラスに operator == があるかどうかを判断するヘルパー関数です。 |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | 特定のクラスに operator == があるかどうかを判断するヘルパー関数です。 |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | コレクションの最初の要素を取得しようとします。 |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | 述語関数を満たすコレクションの最初の要素を取得しようとします。 |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | コレクションの最後の要素を取得しようとします。 |
## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | operator == の存在をチェックするためのダミー typedef。