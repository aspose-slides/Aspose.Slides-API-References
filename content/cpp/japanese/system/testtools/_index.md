---
title: TestTools
second_title: C++ 用 Aspose.Slides API リファレンス
description: さまざまな型や関数の基本的なプロパティをチェックする便利なメソッドのセットを提供します。
type: docs
weight: 1925
url: /ja/system/testtools/
---
## TestTools struct

さまざまな型や関数の基本的なプロパティをチェックする便利なメソッドのセットを提供します。

```cpp
class TestTools
```

## メソッド

| Method | Description |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | 関数が任意のタイプの例外をスローするかどうかをチェックします。 |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | 文字列が空かどうかをチェックします。 |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | コレクションが空かどうかをチェックします。 |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | 特定の値が null かどうかをチェックします。[Version](../version/) 算術型および列挙型の場合。 |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | 特定の値が null かどうかをチェックします。[Version](../version/) 非算術型および非列挙型の値の場合。 |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 特定の値が null かどうかをチェックします。[Version](../version/) 非算術型の値の場合。 |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | 特定の値が null かどうかをチェックします。[Version](../version/) キーと値のペアの場合。 |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | 文字列が null かどうかをチェックします。 |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | コレクションが null か空かどうかをチェックします。 |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | 文字列が null か空かどうかをチェックします。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)