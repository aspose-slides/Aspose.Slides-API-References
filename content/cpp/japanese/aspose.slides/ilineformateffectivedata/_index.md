---
title: ILineFormatEffectiveData
second_title: Aspose.Slides for C++ API リファレンス
description: 有効な行書式設定プロパティを含む不変オブジェクトです。
type: docs
weight: 2770
url: /ja/aspose.slides/ilineformateffectivedata/
---
## ILineFormatEffectiveData クラス

有効な行書式設定プロパティを含む不変オブジェクトです。

```cpp
class ILineFormatEffectiveData : public Aspose::Slides::ILineParamSource
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](./)\>) | 2つの[ILineFormatEffectiveData](./) インスタンスが等しいかどうかを判断します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | 行の配置を返します。読み取り専用 [LineAlignment](../linealignment/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | 行の先頭にある矢じりの長さを返します。読み取り専用 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | 行の先頭にある矢じりのスタイルを返します。読み取り専用 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | 行の先頭にある矢じりの幅を返します。読み取り専用 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | 行のキャップスタイルを返します。読み取り専用 [LineCapStyle](../linecapstyle/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | カスタムダッシュパターンを返します。読み取り専用 **float**[]. |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | 行のダッシュスタイルを返します。読み取り専用 [LineDashStyle](../linedashstyle/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | 行の末尾にある矢じりの長さを返します。読み取り専用 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | 行の末尾にある矢じりのスタイルを返します。読み取り専用 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | 行の末尾にある矢じりの幅を返します。読み取り専用 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormatEffectiveData](../ilinefillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | 行の塗りつぶし形式を返します。読み取り専用 [ILineFillFormatEffectiveData](../ilinefillformateffectivedata/)。 |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | 行の結合スタイルを返します。読み取り専用 [LineJoinStyle](../linejoinstyle/)。 |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | 行のミタ制限を返します。読み取り専用 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormatEffectiveData](../isketchformateffectivedata/)\> [get_SketchFormat](./get_sketchformat/)() | 行のスケッチ形式を返します。読み取り専用 [ISketchFormatEffectiveData](../isketchformateffectivedata/)。 |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | 行のスタイルを返します。読み取り専用 [LineStyle](../linestyle/)。 |
| virtual **double** [get_Width](./get_width/)() | 行の幅を返します。読み取り専用 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文によるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文によるロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

このインターフェイスは、[ILineFormat](../ilineformat/) インターフェイスと組み合わせて、継承が適用された効果的な書式設定値を返すために使用されます。

## 参考

* クラス [ILineParamSource](../ilineparamsource/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)