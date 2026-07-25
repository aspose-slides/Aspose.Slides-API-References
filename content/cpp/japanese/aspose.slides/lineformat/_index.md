---
title: LineFormat
second_title: Aspose.Slides for C++ API リファレンス
description: ラインの書式を表します。
type: docs
weight: 4382
url: /ja/aspose.slides/lineformat/
---
## LineFormat クラス


Represents format of a line.

```cpp
class LineFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ILineFormat
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\>) override | 2つの [LineFormat](./) インスタンスが等しいかどうかを判断します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないとされますが、2つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないとされますが、2つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用です。 |
| [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() override | ラインの配置を返します。参照 [LineAlignment](../linealignment/)。 |
| [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() override | ラインの開始時の矢じり長さを返します。参照 [LineArrowheadLength](../linearrowheadlength/)。 |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() override | ラインの開始時の矢じりスタイルを返します。参照 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() override | ラインの開始時の矢じり幅を返します。参照 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() override | ラインのキャップスタイルを返します。参照 [LineCapStyle](../linecapstyle/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() override | カスタムダッシュパターンを返します。参照 **float**[]。 |
| [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() override | ラインのダッシュスタイルを返します。参照 [LineDashStyle](../linedashstyle/)。 |
| [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() override | ラインの終端の矢じり長さを返します。参照 [LineArrowheadLength](../linearrowheadlength/)。 |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() override | ラインの終端の矢じりスタイルを返します。参照 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() override | ラインの終端の矢じり幅を返します。参照 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() override | ラインの塗りつぶしフォーマットを返します。読み取り専用 [ILineFillFormat](../ilinefillformat/)。 |
| **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() override | ラインフォーマットが未定義（作成直後、デフォルト）の場合に true を返します。読み取り専用 **bool**。 |
| [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() override | ラインの結合スタイルを返します。参照 [LineJoinStyle](../linejoinstyle/)。 |
| **float** [get_MiterLimit](./get_miterlimit/)() override | ラインのミタリミットを返します。参照 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() override | ラインのスケッチフォーマットを返します。読み取り専用 [ILineFillFormat](../ilinefillformat/)。 |
| [LineStyle](../linestyle/) [get_Style](./get_style/)() override | ラインスタイルを返します。参照 [LineStyle](../linestyle/)。 |
| **double** [get_Width](./get_width/)() override | ラインの幅を返します。参照 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() override | 継承が適用された有効なラインフォーマットデータを取得します。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) override | ラインの配置を設定します。書き込み [LineAlignment](../linealignment/)。 |
| void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | ラインの開始時の矢じり長さを設定します。書き込み [LineArrowheadLength](../linearrowheadlength/)。 |
| void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | ラインの開始時の矢じりスタイルを設定します。書き込み [LineArrowheadStyle](../linearrowheadstyle/)。 |
| void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | ラインの開始時の矢じり幅を設定します。書き込み [LineArrowheadWidth](../linearrowheadwidth/)。 |
| void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) override | ラインのキャップスタイルを設定します。書き込み [LineCapStyle](../linecapstyle/)。 |
| void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | カスタムダッシュパターンを設定します。書き込み **float**[]。 |
| void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) override | ラインのダッシュスタイルを設定します。書き込み [LineDashStyle](../linedashstyle/)。 |
| void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | ラインの終端の矢じり長さを設定します。書き込み [LineArrowheadLength](../linearrowheadlength/)。 |
| void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | ラインの終端の矢じりスタイルを設定します。書き込み [LineArrowheadStyle](../linearrowheadstyle/)。 |
| void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | ラインの終端の矢じり幅を設定します。書き込み [LineArrowheadWidth](../linearrowheadwidth/)。 |
| void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) override | ラインの結合スタイルを設定します。書き込み [LineJoinStyle](../linejoinstyle/)。 |
| void [set_MiterLimit](./set_miterlimit/)(**float**) override | ラインのミタリミットを設定します。書き込み **float**。 |
| void [set_Style](./set_style/)([LineStyle](../linestyle/)) override | ラインスタイルを設定します。書き込み [LineStyle](../linestyle/)。 |
| void [set_Width](./set_width/)(**double**) override | ラインの幅を設定します。書き込み **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [PVIObject](../pviobject/)
* クラス [ILineFormat](../ilineformat/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)