---
title: IDataLabel
second_title: Aspose.Slides for C++ API リファレンス
description: 系列ラベルを表します。
type: docs
weight: 937
url: /ja/aspose.slides.charts/idatalabel/
---
## IDataLabel クラス

系列ラベルを表します。

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## メソッド

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | パラメータ "text" のテキストで TextFrameForOverriding を初期化します。既に TextFrameForOverriding が初期化されている場合は、そのテキストを単に変更します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | チャート要素の実際の高さを指定します。実際の値を取得するには事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | チャート要素の実際の幅を指定します。実際の値を取得するには事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | チャート要素の実際の x 位置（左）を、チャートの左上隅に対して指定します。実際の値を取得するには事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | チャート要素の実際の上位置を、チャートの左上隅に対して指定します。実際の値を取得するには事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | チャートの高さの比率としてチャート要素の上位置を取得します。読み取り専用 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | データラベルの書式を返します。読み取り専用 [IDataLabelFormat](../idatalabelformat/)。 |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | チャートの高さの比率としてチャート要素の高さを指定します。読み取り **float**。 |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | false はデータラベルが表示されないことを意味し（したがってすべての Show*-フラグ (ShowValue, ...) が false になります）。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | チャートの幅の比率としてチャート要素の右側位置を取得します。読み取り専用 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | チャートテキスト書式を返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | リッチフォーマットテキストを含めることができます。このプロパティが null でない場合、このフォーマット済みテキストは自動生成テキストを上書きします。自動生成テキストはデータラベル、値軸の表示単位ラベル、軸タイトル、チャートタイトル、トレンドラインのラベルの暗黙的なプロパティです。自動生成テキストは [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) プロパティでフォーマットされます。読み取り専用 [ITextFrame](../../aspose.slides/itextframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | ワークブックのデータセルを取得します。IDataLabelFormat::get(set)_ShowLabelValueFromCell プロパティが true の場合に適用されます。 |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | チャートの幅の比率としてチャート要素の幅を指定します。読み取り **float**。 |
| virtual **float** [get_X](../ilayoutable/get_x/)() | チャートの幅の比率としてチャート要素の x 位置（左）を指定します。読み取り **float**。 |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | チャートの高さの比率としてチャート要素の上位置を指定します。読み取り **float**。 |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | [DataLabelFormat](../datalabelformat/) 設定または TextFrameForOverriding.Text の値に基づく実際のラベルテキストを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual void [Hide](./hide/)() | すべての Show*-フラグ (ShowValue, ...) を false に設定してデータラベルを非表示にします。これにより IsVisible は false になります。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースの特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | チャートの高さの比率としてチャート要素の高さを指定します。書き込み **float**。 |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | ワークブックのデータセルを設定します。IDataLabelFormat::get(set)_ShowLabelValueFromCell プロパティが true の場合に適用されます。 |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | チャートの幅の比率としてチャート要素の幅を指定します。書き込み **float**。 |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | チャートの幅の比率としてチャート要素の x 位置（左）を指定します。書き込み **float**。 |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | チャートの高さの比率としてチャート要素の上位置を指定します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ではなく弱ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ILayoutable](../ilayoutable/)
* クラス [IOverridableText](../ioverridabletext/)
* クラス [IActualLayout](../iactuallayout/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)