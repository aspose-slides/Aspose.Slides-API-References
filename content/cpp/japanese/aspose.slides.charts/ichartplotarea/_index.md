---
title: IChartPlotArea
second_title: Aspose.Slides for C++ API リファレンス
description: チャートのタイトルプロパティを表します。
type: docs
weight: 794
url: /ja/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea class


チャートのタイトルプロパティを表します。

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。2 つの NaN は IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、等しいとみなされます。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。2 つの NaN は IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、等しいとみなされます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | チャート要素の実際の高さを指定します。実際の値を取得するには、先にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | チャート要素の実際の幅を指定します。実際の値を取得するには、先にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | チャート要素の左位置（X）を、チャート左上隅からの相対位置として指定します。実際の値を取得するには、先にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | チャート要素の上位置（Y）を、チャート左上隅からの相対位置として指定します。実際の値を取得するには、先にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | チャート要素の上位置をチャートの高さの比率で取得します。読み取り専用 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | プロット領域の書式を返します。読み取り専用 [IFormat](../iformat/)。 |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | チャート要素の高さをチャートの高さの比率で指定します。**float** を読み取ります。 |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | 手動でプロット領域のレイアウトを定義した場合、このプロパティは領域の内部（軸と軸ラベルを除く）または外部（軸と軸ラベルを含む）でレイアウトするかを指定します。[LayoutTargetType](../layouttargettype/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | チャート要素の右位置をチャートの幅の比率で取得します。読み取り専用 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 基底スライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | チャート要素の幅をチャートの幅の比率で指定します。**float** を読み取ります。 |
| virtual **float** [get_X](../ilayoutable/get_x/)() | チャート要素の左位置（X）をチャートの幅の比率で指定します。**float** を読み取ります。 |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | チャート要素の上位置（Y）をチャートの高さの比率で指定します。**float** を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定した値だけ減少させます。 |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | チャート要素の高さをチャートの高さの比率で指定します。**float** を書き込みます。 |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | 手動でプロット領域のレイアウトを定義した場合、このプロパティは領域の内部（軸と軸ラベルを除く）または外部（軸と軸ラベルを含む）でレイアウトするかを指定します。[LayoutTargetType](../layouttargettype/) を書き込みます。 |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | チャート要素の幅をチャートの幅の比率で指定します。**float** を書き込みます。 |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | チャート要素の左位置（X）をチャートの幅の比率で指定します。**float** を書き込みます。 |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | チャート要素の上位置（Y）をチャートの高さの比率で指定します。**float** を書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタを減少させ、戻り値として返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウンタを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウンタを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照項目

* クラス [ILayoutable](../ilayoutable/)
* クラス [IActualLayout](../iactuallayout/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)