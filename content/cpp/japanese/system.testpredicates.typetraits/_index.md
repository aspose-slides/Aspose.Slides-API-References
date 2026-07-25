---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 963
url: /ja/system.testpredicates.typetraits/
---
## 構造体

| 構造体 | 説明 |
| --- | --- |
| [has_data_method](./has_data_method/) | 型に data() メソッドがあるかチェックします。存在する場合は std::true_type を継承し、存在しない場合は std::false_type を継承します。 |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | BitArray 型の特殊化で、そこではアクセスできない boost 型を提供します。 |
| [has_print_to_method](./has_print_to_method/) | 第一引数として対象の型を受け取る PrintTo 関数のオーバーロードがあるかチェックします。オーバーロードが存在すれば std::true_type を継承し、存在しなければ std::false_type を継承します。 |
| [IsCppContainer](./iscppcontainer/) | 特定の型が STL スタイルのコンテナかどうかをチェックします。そのために iterator と const_iterator メンバー型の存在を確認します。両方が存在すれば std::true_type を継承し、そうでなければ std::false_type を継承します。 |
| [IsEnumerable](./isenumerable/) | 型が [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) の特殊化を基底型として持つかチェックします。持つ場合は value メンバーが true に設定され、そうでない場合は false に設定されます。 |
| [LargestFPType](./largestfptype/) | 提供される中で最も長い浮動小数点型のエイリアスを提供します。浮動小数点型以外は無視します。 |
## 型定義

| 型定義 | 説明 |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | **T1** が算術型で **T2** が浮動小数点型、あるいはその逆であるかをチェックします。該当すれば value メンバーが true に設定され、そうでなければ false になります。 |
| [AnyOfDecimal](./anyofdecimal/) | 型引数のいずれかが [System::Decimal](../system/decimal/) であるかをチェックします。該当すれば value メンバーが true に設定され、そうでなければ false になります。 |
| [IsArray](./isarray/) | 型が [System::Array](../system/array/) の特殊化であるかをチェックします。該当すれば value メンバーが true に設定され、そうでなければ false に設定されます。 |
| [IsList](./islist/) | 型が [System::Collections::Generic::List](../system.collections.generic/list/) の特殊化であるかをチェックします。該当すれば value メンバーが true に設定され、そうでなければ false に設定されます。 |
| [BothArrayOrList](./botharrayorlist/) | 両方の型引数が配列またはリストであるかをチェックします。該当すれば value メンバーが true に設定され、そうでなければ false に設定されます。 |
| [BothEnumerable](./bothenumerable/) | 両方の型引数が IEnumerable であるかをチェックします。該当すれば value メンバーが true に設定され、そうでなければ false に設定されます。 |