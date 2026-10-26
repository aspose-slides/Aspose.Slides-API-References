---
title: ILineFormat
second_title: Aspose.Slides for C++ API リファレンス
description: ラインの書式を表します。
type: docs
weight: 2757
url: /ja/aspose.slides/ilineformat/
---
## ILineFormat クラス


ラインの書式を表します。

```cpp
class ILineFormat : public Aspose::Slides::ILineParamSource
```

## メソッド

| Method | 説明 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](./)\>) | 2 つの [LineFormat](../lineformat/) インスタンスが等しいかどうかを判定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的専用です。 |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | ラインの配置を返します。読み取り [LineAlignment](../linealignment/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | ラインの開始位置における矢じりの長さを返します。読み取り [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | ラインの開始位置における矢じりのスタイルを返します。読み取り [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | ラインの開始位置における矢じりの幅を返します。読み取り [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | ラインのキャップスタイルを返します。読み取り [LineCapStyle](../linecapstyle/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | カスタム破線パターンを返します。読み取り **float**[]。 |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | ラインの破線スタイルを返します。読み取り [LineDashStyle](../linedashstyle/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | ラインの終端における矢じりの長さを返します。読み取り [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | ラインの終端における矢じりのスタイルを返します。読み取り [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | ラインの終端における矢じりの幅を返します。読み取り [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() | ラインの塗りつぶし形式を返します。読み取り専用 [ILineFillFormat](../ilinefillformat/)。 |
| virtual **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() | ライン書式が定義されていない場合 (作成直後、デフォルト) に true を返します。読み取り専用 **bool**。 |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | ラインの結合スタイルを返します。読み取り [LineJoinStyle](../linejoinstyle/)。 |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | ラインのマイターリミットを返します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() | ラインのスケッチ形式を返します。読み取り専用 [ISketchFormat](../isketchformat/)。 |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | ラインのスタイルを返します。読み取り [LineStyle](../linestyle/)。 |
| virtual **double** [get_Width](./get_width/)() | ラインの幅を返します。読み取り **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() | 継承が適用された有効なライン書式データを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) | ラインの配置を設定します。書き込み [LineAlignment](../linealignment/)。 |
| virtual void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | ラインの開始位置における矢じりの長さを設定します。書き込み [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | ラインの開始位置における矢じりのスタイルを設定します。書き込み [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | ラインの開始位置における矢じりの幅を設定します。書き込み [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) | ラインのキャップスタイルを設定します。書き込み [LineCapStyle](../linecapstyle/)。 |
| virtual void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | カスタム破線パターンを設定します。書き込み **float**[]。 |
| virtual void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) | ラインの破線スタイルを設定します。書き込み [LineDashStyle](../linedashstyle/)。 |
| virtual void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | ラインの終端における矢じりの長さを設定します。書き込み [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | ラインの終端における矢じりのスタイルを設定します。書き込み [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | ラインの終端における矢じりの幅を設定します。書き込み [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) | ラインの結合スタイルを設定します。書き込み [LineJoinStyle](../linejoinstyle/)。 |
| virtual void [set_MiterLimit](./set_miterlimit/)(**float**) | ラインのマイターリミットを設定します。書き込み **float**。 |
| virtual void [set_Style](./set_style/)([LineStyle](../linestyle/)) | ラインのスタイルを設定します。書き込み [LineStyle](../linestyle/)。 |
| virtual void [set_Width](./set_width/)(**double**) | ラインの幅を設定します。書き込み **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します (共有ではなく)。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ILineParamSource](../ilineparamsource/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)