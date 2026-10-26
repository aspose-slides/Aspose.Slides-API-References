---
title: "System::MemoryExtensions"
second_title: Aspose.Slides for C++ API リファレンス
description: スパンや配列のメモリ操作のための拡張メソッドを提供します。
type: docs
weight: 625
url: /ja/system.memoryextensions/
---
スパンと配列のメモリ操作向けの拡張メソッドを提供します。

## 関数

| 関数 | 説明 |
| --- | --- |
| [Span](../system/span/)\<T\> [AsSpan](./asspan/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, **int32_t**, **int32_t**) | 配列からスパンを作成します。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [AsSpan](./asspan/)(const [String](../system/string/)\&, **int32_t**, **int32_t**) | 文字列から読み取り専用スパンを作成します。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TComparable\&) | ソート済みスパンで二分検索を実行します。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | カスタム比較子を使用してソート済みスパンで二分検索を実行します。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const TComparable\&) | 可変のソート済みスパンで二分検索を実行します。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | カスタム比較子を使用して可変のソート済みスパンで二分検索を実行します。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 2 つのスパン間の共通プレフィックスの長さを取得します。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 可変スパンと読み取り専用スパン間の共通プレフィックスの長さを取得します。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 2 つの可変スパン間の共通プレフィックスの長さを取得します。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | カスタム等価比較子を使用して 2 つのスパン間の共通プレフィックスの長さを取得します。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | カスタム等価比較子を使用して可変スパンと読み取り専用スパン間の共通プレフィックスの長さを取得します。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | カスタム等価比較子を使用して 2 つの可変スパン間の共通プレフィックスの長さを取得します。 |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 読み取り専用スパンが特定の値を含んでいるか確認します。 |
| **bool** [Contains](./contains/)(const [Span](../system/span/)\<T\>\&, const T\&) | 可変スパンが特定の値を含んでいるか確認します。 |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 指定された比較ルールで文字スパンが別の文字スパンを含んでいるか確認します。 |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 読み取り専用スパンが 2 つの値のいずれかを含んでいるか確認します。 |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 読み取り専用スパンが 3 つの値のいずれかを含んでいるか確認します。 |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 可変スパンが 2 つの値のいずれかを含んでいるか確認します。 |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 可変スパンが 3 つの値のいずれかを含んでいるか確認します。 |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 読み取り専用スパンが別のスパンから任意の値を含んでいるか確認します。 |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 可変スパンが読み取り専用スパンから任意の値を含んでいるか確認します。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 読み取り専用スパンが指定された 3 つの値以外の要素を含んでいるか確認します。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 可変スパンが指定された 3 つの値以外の要素を含んでいるか確認します。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 読み取り専用スパンが指定された 2 つの値以外の要素を含んでいるか確認します。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 可変スパンが指定された 2 つの値以外の要素を含んでいるか確認します。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 読み取り専用スパンが指定された値以外の要素を含んでいるか確認します。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 可変スパンが指定された値以外の要素を含んでいるか確認します。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 読み取り専用スパンが別のスパンにある要素以外を含んでいるか確認します。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 可変スパンが読み取り専用スパンにある要素以外を含んでいるか確認します。 |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 読み取り専用スパンが指定された範囲外の要素を含んでいるか確認します。 |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 可変スパンが指定された範囲外の要素を含んでいるか確認します。 |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 読み取り専用スパンが指定された範囲内の要素を含んでいるか確認します。 |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 可変スパンが指定された範囲内の要素を含んでいるか確認します。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, [Span](../system/span/)\<T\>\&) | 配列からスパンへ要素をコピーします。 |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 読み取り専用スパン内で値の出現回数を数えます。 |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 別の読み取り専用スパン内でスパンの出現回数を数えます。 |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const T\&) | Span<T> 内で単一の値の出現回数を数えます。 |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T> 内で ReadOnlySpan<T> の出現回数を数えます。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ReadOnlySpan<T> が単一の値で終わるかどうかを判定します。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ReadOnlySpan<T> が別の ReadOnlySpan<T> で終わるかどうかを判定します。 |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T> が ReadOnlySpan<T> で終わるかどうかを判定します。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | ReadOnlySpan<T> が Span<T> で終わるかどうかを判定します。 |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Span<T> が別の Span<T> で終わるかどうかを判定します。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | StringComparison を使用して、ReadOnlySpan<char16_t> が指定された値で終わるかどうかを判定します。 |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 別の ReadOnlySpan<T> 内で ReadOnlySpan<T> の値のインデックスを検索します。 |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ReadOnlySpan<T> 内で単一の値のインデックスを検索します。 |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T> 内で ReadOnlySpan<T> の値のインデックスを検索します。 |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | Span<T> 内で単一の値のインデックスを検索します。 |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | StringComparison を使用して、ReadOnlySpan<char16_t> 内で ReadOnlySpan<char16_t> の値のインデックスを検索します。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ReadOnlySpan<T> 内で指定された 2 つの値のいずれかが最初に出現するインデックスを検索します。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ReadOnlySpan<T> 内で指定された 3 つの値のいずれかが最初に出現するインデックスを検索します。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Span<T> 内で指定された 2 つの値のいずれかが最初に出現するインデックスを検索します。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Span<T> 内で指定された 3 つの値のいずれかが最初に出現するインデックスを検索します。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 別の ReadOnlySpan<T> 内でスパンからの任意の値が最初に出現するインデックスを検索します。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T> 内でスパンからの任意の値が最初に出現するインデックスを検索します。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ReadOnlySpan<T> 内で指定された値と等しくない最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ReadOnlySpan<T> 内で指定された 2 つの値のいずれとも等しくない最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ReadOnlySpan<T> 内で指定された 3 つの値のいずれとも等しくない最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | Span<T> 内で指定された値と等しくない最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Span<T> 内で指定された 2 つの値のいずれとも等しくない最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Span<T> 内で指定された 3 つの値のいずれとも等しくない最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 値のスパン内でいずれの値とも等しくない最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T> 内で値のスパン内のいずれの値とも等しくない最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ReadOnlySpan<T> 内で指定された範囲外の最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Span<T> 内で指定された範囲外の最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ReadOnlySpan<T> 内で指定された範囲内の最初の要素のインデックスを検索します。 |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Span<T> 内で指定された範囲内の最初の要素のインデックスを検索します。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | スパン内でシーケンスの最後の出現位置を検索します。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | スパン内で単一の値の最後の出現位置を検索します。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 可変スパン内でシーケンスの最後の出現位置を検索します。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | 可変スパン内で単一の値の最後の出現位置を検索します。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 指定された文字列比較を使用してスパン内で値の最後の出現位置を検索します。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | スパン内で指定された 3 つの値のいずれかの最後の出現位置を検索します。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 可変スパン内で指定された 3 つの値のいずれかの最後の出現位置を検索します。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | スパン内で指定された 2 つの値のいずれかの最後の出現位置を検索します。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 可変スパン内で指定された 2 つの値のいずれかの最後の出現位置を検索します。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | スパン内でシーケンスからの任意の値の最後の出現位置を検索します。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 可変スパン内でシーケンスからの任意の値の最後の出現位置を検索します。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 可変スパン内で可変シーケンスからの任意の値の最後の出現位置を検索します。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | スパン内で、指定された 3 つの値を除く任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 変更可能なスパン内で、指定された 3 つの値を除く任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | スパン内で、指定された 2 つの値を除く任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 変更可能なスパン内で、指定された 2 つの値を除く任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | スパン内で、指定された値を除く任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 変更可能なスパン内で、指定された値を除く任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | スパン内で、シーケンスからの値を除く任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 変更可能なスパン内で、シーケンスからの値を除く任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 変更可能なスパン内で、変更可能なシーケンスからの値を除く任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | スパン内で、指定された範囲外の任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 変更可能なスパン内で、指定された範囲外の任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | スパン内で、指定された範囲内の任意の要素の最後の出現を検索します。 |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 変更可能なスパン内で、指定された範囲内の任意の要素の最後の出現を検索します。 |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 2 つの ReadOnlySpans がメモリ上でオフセットを計算せずに重なっているかどうかを判断します。 |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | [Span](../system/span/) と [ReadOnlySpan](../system/readonlyspan/) がメモリ上でオフセットを計算せずに重なっているかどうかを判断します。 |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | 2 つの ReadOnlySpans がメモリ上で重なっているかを判断し、オフセットを計算します。 |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | [Span](../system/span/) と [ReadOnlySpan](../system/readonlyspan/) がメモリ上で重なっているかを判断し、オフセットを計算します。 |
| void [Replace](./replace/)([Span](../system/span/)\<T\>\&, const T\&, const T\&) | [Span](../system/span/) 内のすべての値の出現を新しい値に置き換えます。 |
| void [Replace](./replace/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ソースからデスティネーションへ要素をコピーし、コピー中に指定された値を置き換えます。 |
| void [Reverse](./reverse/)([Span](../system/span/)\<T\>\&) | [Span](../system/span/) の要素の順序をその場で逆転させます。 |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 2 つの ReadOnlySpans を辞書順で比較します。 |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | [Span](../system/span/) と [ReadOnlySpan](../system/readonlyspan/) を辞書順で比較します。 |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | [ReadOnlySpan](../system/readonlyspan/) と [Span](../system/span/) を辞書順で比較します。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 2 つの ReadOnlySpans が同じ順序で同一の要素を含んでいるかどうかを判断します。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | [Span](../system/span/) と [ReadOnlySpan](../system/readonlyspan/) が同じ順序で同一の要素を含んでいるかどうかを判断します。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 2 つの ReadOnlySpans がカスタム比較子を使用して等しい要素を含んでいるかどうかを判断します。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | [Span](../system/span/) と [ReadOnlySpan](../system/readonlyspan/) がカスタム比較子を使用して等しい要素を含んでいるかどうかを判断します。 |
| void [Sort](./sort/)(const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | カスタム比較子を使用して [Span](../system/span/) をソートします。 |
| void [Sort](./sort/)([Span](../system/span/)\<T\>\&) | 既定の比較を使用して [Span](../system/span/) をソートします。 |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | カスタム比較子を使用してキーと値のペアをソートします（キーと値が一緒にソートされます） |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, [System::Comparison](../system/comparison/)\<TKey\>) | 比較デリゲートを使用してキーと値のペアをソートします。 |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&) | 既定の比較を使用してキーと値のペアをソートします。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | スパンが指定された値で始まるかどうかをチェックします。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | スパンが指定された値のスパンで始まるかどうかをチェックします。 |
| **bool** [StartsWith](./startswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 変更可能なスパンが指定された読み取り専用値スパンで始まるかどうかをチェックします。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 読み取り専用スパンが指定された変更可能な値スパンで始まるかどうかをチェックします。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 文字スパンが文字列比較を使用して指定された値スパンで始まるかどうかをチェックします。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<[String](../system/string/)\>\&, const char16_t *) | 文字列スパンが指定された文字配列で始まるかどうかをチェックします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, T) | 型付きスパンの両端から指定された要素をトリムします。 |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, T) | 変更可能な型付きスパンの両端から指定された要素をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 型付きスパンの両端から指定された要素をトリムします。 |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 変更可能な型付きスパンの両端から指定された要素をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 文字スパンの両端から空白文字をトリムします。 |
| [Span](../system/span/)\<char16_t\> [Trim](./trim/)([Span](../system/span/)\<char16_t\>\&) | 変更可能な文字スパンの両端から空白文字をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 型付きスパンの末尾から指定された要素をトリムします。 |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const T\&) | 変更可能な型付きスパンの末尾から指定された要素をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 型付きスパンの末尾から指定された要素をトリムします。 |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 変更可能な型付きスパンの末尾から指定された要素をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 文字スパンの末尾から空白文字をトリムします。 |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&) | 変更可能な文字スパンの末尾から空白文字をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | 文字スパンの末尾から指定された文字をトリムします。 |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, char16_t) | 変更可能な文字スパンの末尾から指定された文字をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 文字スパンの末尾から指定された文字をトリムします。 |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 変更可能な文字スパンの末尾から指定された文字をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 型付きスパンの先頭から指定された要素をトリムします。 |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const T\&) | 変更可能な型付きスパンの先頭から指定された要素をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 型付きスパンの先頭から指定された要素をトリムします。 |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 変更可能な型付きスパンの先頭から指定された要素をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 文字スパンの先頭から空白文字をトリムします。 |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&) | 変更可能な文字スパンの先頭から空白文字をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | 文字スパンの先頭から指定された文字をトリムします。 |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, char16_t) | 変更可能な文字スパンの先頭から指定された文字をトリムします。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 文字スパンの先頭から指定された文字をトリムします。 |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 変更可能な文字スパンの先頭から指定された文字をトリムします。 |
| **int32_t** [CompareTo](./compareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 指定された文字列比較ルールで 2 つの文字スパンを比較します。 |
| **bool** [Equals](./equals/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | StringComparison を使用して 2 つの ReadOnlySpan<char16_t> の等価性を比較します。 |
| **bool** [IsWhiteSpace](./iswhitespace/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | スパン全体が空白文字だけで構成されているかどうかをチェックします。 |
| **int32_t** [ToLower](./tolower/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | 指定されたカルチャを使用して文字を小文字に変換します。 |
| **int32_t** [ToLowerInvariant](./tolowerinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | 不変カルチャを使用して文字を小文字に変換します。 |
| **int32_t** [ToUpper](./toupper/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | 指定されたカルチャを使用して文字を大文字に変換します。 |
| **int32_t** [ToUpperInvariant](./toupperinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | 不変カルチャを使用して文字を大文字に変換します。 |