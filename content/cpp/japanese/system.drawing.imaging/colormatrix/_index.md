---
title: ColorMatrix
second_title: Aspose.Slides for C++ API リファレンス
description: "RGBAW カラースペースの座標を含む 5x5 行列を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション障害が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 27
url: /ja/system.drawing.imaging/colormatrix/
---
## ColorMatrix クラス

RGBAW カラースペースの座標を含む 5x5 行列を表します。 このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション障害が発生します。 常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡すようにしてください。

```cpp
class ColorMatrix : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | [ColorMatrix](./) クラスの新しいインスタンスを構築し、単位行列の値で初期化します。 |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | [ColorMatrix](./) クラスの新しいインスタンスを構築し、指定された値で初期化します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的専用です。 |
| **float** [get_Matrix00](./get_matrix00/)() const | 0 行目 0 列目の値を返します。 |
| **float** [get_Matrix01](./get_matrix01/)() const | 0 行目 1 列目の値を返します。 |
| **float** [get_Matrix02](./get_matrix02/)() const | 0 行目 2 列目の値を返します。 |
| **float** [get_Matrix03](./get_matrix03/)() const | 0 行目 3 列目の値を返します。 |
| **float** [get_Matrix04](./get_matrix04/)() const | 0 行目 4 列目の値を返します。 |
| **float** [get_Matrix10](./get_matrix10/)() const | 1 行目 0 列目の値を返します。 |
| **float** [get_Matrix11](./get_matrix11/)() const | 1 行目 1 列目の値を返します。 |
| **float** [get_Matrix12](./get_matrix12/)() const | 1 行目 2 列目の値を返します。 |
| **float** [get_Matrix13](./get_matrix13/)() const | 1 行目 3 列目の値を返します。 |
| **float** [get_Matrix14](./get_matrix14/)() const | 1 行目 4 列目の値を返します。 |
| **float** [get_Matrix20](./get_matrix20/)() const | 2 行目 0 列目の値を返します。 |
| **float** [get_Matrix21](./get_matrix21/)() const | 2 行目 1 列目の値を返します。 |
| **float** [get_Matrix22](./get_matrix22/)() const | 2 行目 2 列目の値を返します。 |
| **float** [get_Matrix23](./get_matrix23/)() const | 2 行目 3 列目の値を返します。 |
| **float** [get_Matrix24](./get_matrix24/)() const | 2 行目 4 列目の値を返します。 |
| **float** [get_Matrix30](./get_matrix30/)() const | 3 行目 0 列目の値を返します。 |
| **float** [get_Matrix31](./get_matrix31/)() const | 3 行目 1 列目の値を返します。 |
| **float** [get_Matrix32](./get_matrix32/)() const | 3 行目 2 列目の値を返します。 |
| **float** [get_Matrix33](./get_matrix33/)() const | 3 行目 3 列目の値を返します。 |
| **float** [get_Matrix34](./get_matrix34/)() const | 3 行目 4 列目の値を返します。 |
| **float** [get_Matrix40](./get_matrix40/)() const | 4 行目 0 列目の値を返します。 |
| **float** [get_Matrix41](./get_matrix41/)() const | 4 行目 1 列目の値を返します。 |
| **float** [get_Matrix42](./get_matrix42/)() const | 4 行目 2 列目の値を返します。 |
| **float** [get_Matrix43](./get_matrix43/)() const | 4 行目 3 列目の値を返します。 |
| **float** [get_Matrix44](./get_matrix44/)() const | 4 行目 4 列目の値を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| **float** [idx_get](./idx_get/)(int, int) | 指定された行と列の値を返します。 |
| **float** [idx_set](./idx_set/)(int, int, **float**) | 行列の指定された位置に指定された値を設定します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースへの特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースへの特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Matrix00](./set_matrix00/)(**float**) | 0 行目 0 列目に値を設定します。 |
| void [set_Matrix01](./set_matrix01/)(**float**) | 0 行目 1 列目に値を設定します。 |
| void [set_Matrix02](./set_matrix02/)(**float**) | 0 行目 2 列目に値を設定します。 |
| void [set_Matrix03](./set_matrix03/)(**float**) | 0 行目 3 列目に値を設定します。 |
| void [set_Matrix04](./set_matrix04/)(**float**) | 0 行目 4 列目に値を設定します。 |
| void [set_Matrix10](./set_matrix10/)(**float**) | 1 行目 0 列目に値を設定します。 |
| void [set_Matrix11](./set_matrix11/)(**float**) | 1 行目 1 列目に値を設定します。 |
| void [set_Matrix12](./set_matrix12/)(**float**) | 1 行目 2 列目に値を設定します。 |
| void [set_Matrix13](./set_matrix13/)(**float**) | 1 行目 3 列目に値を設定します。 |
| void [set_Matrix14](./set_matrix14/)(**float**) | 1 行目 4 列目に値を設定します。 |
| void [set_Matrix20](./set_matrix20/)(**float**) | 2 行目 0 列目に値を設定します。 |
| void [set_Matrix21](./set_matrix21/)(**float**) | 2 行目 1 列目に値を設定します。 |
| void [set_Matrix22](./set_matrix22/)(**float**) | 2 行目 2 列目に値を設定します。 |
| void [set_Matrix23](./set_matrix23/)(**float**) | 2 行目 3 列目に値を設定します。 |
| void [set_Matrix24](./set_matrix24/)(**float**) | 2 行目 4 列目に値を設定します。 |
| void [set_Matrix30](./set_matrix30/)(**float**) | 3 行目 0 列目に値を設定します。 |
| void [set_Matrix31](./set_matrix31/)(**float**) | 3 行目 1 列目に値を設定します。 |
| void [set_Matrix32](./set_matrix32/)(**float**) | 3 行目 2 列目に値を設定します。 |
| void [set_Matrix33](./set_matrix33/)(**float**) | 3 行目 3 列目に値を設定します。 |
| void [set_Matrix34](./set_matrix34/)(**float**) | 3 行目 4 列目に値を設定します。 |
| void [set_Matrix40](./set_matrix40/)(**float**) | 4 行目 0 列目に値を設定します。 |
| void [set_Matrix41](./set_matrix41/)(**float**) | 4 行目 1 列目に値を設定します。 |
| void [set_Matrix42](./set_matrix42/)(**float**) | 4 行目 2 列目に値を設定します。 |
| void [set_Matrix43](./set_matrix43/)(**float**) | 4 行目 3 列目に値を設定します。 |
| void [set_Matrix44](./set_matrix44/)(**float**) | 4 行目 4 列目に値を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Drawing::Imaging](../)
* ライブラリ [Aspose.Slides](../../)