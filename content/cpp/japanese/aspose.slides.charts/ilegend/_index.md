---
title: ILegend
second_title: Aspose.Slides for C++ API リファレンス
description: チャートの凡例プロパティを表します。
type: docs
weight: 1080
url: /ja/aspose.slides.charts/ilegend/
---
## ILegend クラス


チャートの凡例プロパティを表します。

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | チャート要素の実際の高さを指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | チャート要素の実際の幅を指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | チャート要素の実際の X 位置（左）を、チャートの左上隅に対する相対位置で指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | チャート要素の実際の上位置を、チャートの左上隅に対する相対位置で指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | チャート要素の上位置をチャートの高さの割合で取得します。読み取り専用 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | 凡例エントリを取得します。読み取り専用 [ILegendEntryCollection](../ilegendentrycollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | 指定されたインデックスのチャート内データポイントに対応する凡例エントリのプロパティを取得します。チャートタイプが bar-of-pie、exploded pie、exploded pie 3D、pie、pie 3D、pie-of-pie の場合、データポイントは最初のシリーズから取得されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 凡例の形式を返します。読み取り専用 [IFormat](../iformat/)。 |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | チャート要素の高さをチャートの高さの割合で指定します。**float** を読み取ります。 |
| virtual **bool** [get_Overlay](./get_overlay/)() | 他のチャート要素が凡例と重なってもよいかを決定します。**bool** を読み取ります。 |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | チャート上の凡例の位置を指定します。X、Y、Width、Height プロパティの NaN でない値はこのプロパティの効果を上書きします。[LegendPositionType](../legendpositiontype/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | チャート要素の右位置をチャートの幅の割合で取得します。読み取り専用 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | チャートのテキスト形式を返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | チャート要素の幅をチャートの幅の割合で指定します。**float** を読み取ります。 |
| virtual **float** [get_X](../ilayoutable/get_x/)() | チャート要素の X 位置（左）をチャートの幅の割合で指定します。**float** を読み取ります。 |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | チャート要素の上位置をチャートの高さの割合で指定します。**float** を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | チャート要素の高さをチャートの高さの割合で指定します。**float** を書き込みます。 |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | 他のチャート要素が凡例と重なることを許可するかどうかを決定します。**bool** を書き込みます。 |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | チャート上の凡例の位置を指定します。X、Y、Width、Height プロパティの NaN でない値はこのプロパティの効果を上書きします。[LegendPositionType](../legendpositiontype/) を書き込みます。 |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | チャート要素の幅をチャートの幅の割合で指定します。**float** を書き込みます。 |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | チャート要素の X 位置（左）をチャートの幅の割合で指定します。**float** を書き込みます。 |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | チャート要素の上位置をチャートの高さの割合で指定します。**float** を書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参考

* クラス [ILayoutable](../ilayoutable/)
* クラス [IFormattedTextContainer](../iformattedtextcontainer/)
* クラス [IActualLayout](../iactuallayout/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)