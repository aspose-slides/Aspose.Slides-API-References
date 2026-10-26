---
title: ChartPlotArea
second_title: Aspose.Slides for C++ API リファレンス
description: チャートが描画される矩形を表します。
type: docs
weight: 248
url: /ja/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea クラス

チャートが描画される矩形を表します。

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 2 つの NaN が等しいとみなされる C# スタイルの浮動小数点比較をエミュレートします（IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくありません）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 2 つの NaN が等しいとみなされる C# スタイルの浮動小数点比較をエミュレートします（IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくありません）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部的な目的のみです。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | チャート要素の実際の高さを指定します。実際の値を取得するには、先にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。読み取り **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | チャート要素の実際の幅を指定します。実際の値を取得するには、先にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。読み取り **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | チャートの左上隅に対するチャート要素の実際の x 位置（左）を指定します。実際の値を取得するには、先にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。読み取り **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | チャートの左上隅に対するチャート要素の実際の上位置を指定します。実際の値を取得するには、先にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。読み取り **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 下部。読み取り専用 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/)。読み取り専用 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | プロット領域の書式を返します。読み取り専用 [IFormat](../iformat/)。 |
| **float** [get_Height](./get_height/)() override | プロット領域のバウンディングボックスの高さをチャートの高さの割合（0 から 1）で返します。読み取り **float**。 |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | 位置の計算方法を定義します: true – 自動計算; X、Y、Width、Height プロパティで定義。読み取り専用 **bool**。 |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | プロット領域のレイアウトが手動で定義されている場合、このプロパティは内部（軸と軸ラベルを除く）または外部（軸と軸ラベルを含む）でレイアウトするかを指定します。読み取り [LayoutTargetType](../layouttargettype/)。 |
| **float** [get_Right](./get_right/)() override | 右。読み取り専用 **float**。 |
| **float** [get_Width](./get_width/)() override | プロット領域のバウンディングボックスの幅をチャートの幅の割合（0 から 1）で返します。読み取り **float**。 |
| **float** [get_X](./get_x/)() override | プロット領域のバウンディングボックスの左上隅の x 座標をチャートの幅の割合（0 から 1）で返します。読み取り **float**。 |
| **float** [get_Y](./get_y/)() override | プロット領域のバウンディングボックスの左上隅の y 座標をチャートの高さの割合（0 から 1）で返します。読み取り **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を有効にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を有効にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Height](./set_height/)(**float**) override | プロット領域のバウンディングボックスの高さをチャートの高さの割合（0 から 1）で設定します。書き込み **float**。 |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | プロット領域のレイアウトが手動で定義されている場合、このプロパティは内部（軸と軸ラベルを除く）または外部（軸と軸ラベルを含む）でレイアウトするかを指定します。書き込み [LayoutTargetType](../layouttargettype/)。 |
| void [set_Width](./set_width/)(**float**) override | プロット領域のバウンディングボックスの幅をチャートの幅の割合（0 から 1）で設定します。書き込み **float**。 |
| void [set_X](./set_x/)(**float**) override | プロット領域のバウンディングボックスの左上隅の x 座標をチャートの幅の割合（0 から 1）で設定します。書き込み **float**。 |
| void [set_Y](./set_y/)(**float**) override | プロット領域のバウンディングボックスの左上隅の y 座標をチャートの高さの割合（0 から 1）で設定します。書き込み **float**。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させ、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [DomObject](../../aspose.slides/domobject/)
* クラス [IChartPlotArea](../ichartplotarea/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)