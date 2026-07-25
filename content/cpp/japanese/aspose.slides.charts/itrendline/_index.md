---
title: ITrendline
second_title: Aspose.Slides for C++ API リファレンス
description: クラスはチャート系列のトレンドラインを表します
type: docs
weight: 1223
url: /ja/aspose.slides.charts/itrendline/
---
## ITrendline クラス

クラスはチャート系列のトレンドラインを表します

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | パラメータ \"text\" のテキストで TextFrameForOverriding を初期化します。TextFrameForOverriding がすでに初期化されている場合は、テキストを単に変更します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual **double** [get_Backward](./get_backward/)() | トレンドラインが、トレンド対象系列のデータの前に伸びるカテゴリ数（または散布図の単位数）を指定します。散布図および非散布図では、値は非負の任意の数である必要があります。読み取り **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | トレンドラインの方程式がチャート上（Rsquaredvalue と同じラベルで）表示されることを指定します。読み取り **bool**。 |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | トレンドラインの R-squared 値がチャート上（方程式と同じラベルで）表示されることを指定します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | トレンドラインの書式を表します。読み取り [IFormat](../iformat/)。 |
| virtual **double** [get_Forward](./get_forward/)() | トレンドラインが、トレンド対象系列のデータの後に伸びるカテゴリ数（または散布図の単位数）を指定します。散布図および非散布図では、値は非負の任意の数である必要があります。読み取り **double**。 |
| virtual **double** [get_Intercept](./get_intercept/)() | トレンドラインが y 軸と交差する値を指定します。このプロパティはトレンドラインの種類が exp、linear、または poly の場合にのみサポートされます。読み取り **double**。 |
| virtual **uint8_t** [get_Order](./get_order/)() | 多項式トレンドラインの次数を指定します。他のトレンドラインの種類では無視されます。値は 2 から 6 の間でなければなりません。読み取り **uint8_t**。 |
| virtual **uint8_t** [get_Period](./get_period/)() | 移動平均トレンドラインの期間を指定します。他のトレンドラインのバリエーションでは無視されます。値は 2 から 255 の間でなければなりません。読み取り **uint8_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | このトレンドラインに関連する凡例エントリを表します。読み取り専用 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 基本スライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | チャートテキスト書式を返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | リッチ書式テキストを含めることができます。このプロパティが null でない場合、この書式テキストは自動生成テキストを上書きします。自動生成テキストはデータラベル、値軸の表示単位ラベル、軸タイトル、チャートタイトル、トレンドラインのラベルの暗黙的なプロパティです。自動生成テキストは [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) プロパティで書式設定されます。読み取り専用 [ITextFrame](../../aspose.slides/itextframe/)。 |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | トレンドラインの名前を取得します。読み取り [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | トレンドラインの種類を取得します。読み取り [TrendlineType](../trendlinetype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化で、文字列と nullptr のケースを扱います。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化で、文字列のケースを扱います。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウンタを指定された値だけ減少させます。 |
| virtual void [set_Backward](./set_backward/)(**double**) | トレンドラインが、トレンド対象系列のデータの前に伸びるカテゴリ数（または散布図の単位数）を指定します。散布図および非散布図では、値は非負の任意の数である必要があります。書き込み **double**。 |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | トレンドラインの方程式がチャート上（Rsquaredvalue と同じラベルで）表示されることを指定します。書き込み **bool**。 |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | トレンドラインの R-squared 値がチャート上（方程式と同じラベルで）表示されることを指定します。書き込み **bool**。 |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | トレンドラインの書式を表します。書き込み [IFormat](../iformat/)。 |
| virtual void [set_Forward](./set_forward/)(**double**) | トレンドラインが、トレンド対象系列のデータの後に伸びるカテゴリ数（または散布図の単位数）を指定します。散布図および非散布図では、値は非負の任意の数である必要があります。書き込み **double**。 |
| virtual void [set_Intercept](./set_intercept/)(**double**) | トレンドラインが y 軸と交差する値を指定します。このプロパティはトレンドラインの種類が exp、linear、または poly の場合にのみサポートされます。書き込み **double**。 |
| virtual void [set_Order](./set_order/)(**uint8_t**) | 多項式トレンドラインの次数を指定します。他のトレンドラインの種類では無視されます。値は 2 から 6 の間でなければなりません。書き込み **uint8_t**。 |
| virtual void [set_Period](./set_period/)(**uint8_t**) | 移動平均トレンドラインの期間を指定します。他のトレンドラインのバリエーションでは無視されます。値は 2 から 255 の間でなければなりません。書き込み **uint8_t**。 |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | トレンドラインの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | トレンドラインの種類を設定します。書き込み [TrendlineType](../trendlinetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタ（shared ではなく）に設定します。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 参照カウンタをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IOverridableText](../ioverridabletext/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)