---
title: ChartTitle
second_title: Aspose.Slides for C++ API リファレンス
description: チャートタイトルのプロパティを表します。
type: docs
weight: 326
url: /ja/aspose.slides.charts/charttitle/
---
## ChartTitle クラス

Represents chart title properties.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | パラメータ \"text\" のテキストで TextFrameForOverriding を初期化します。TextFrameForOverriding が既に初期化されている場合は、単にテキストを変更します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的専用です。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | チャート要素の実際の高さを指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。読み取り **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | チャート要素の実際の幅を指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。読み取り **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | チャートの左上隅を基準としたチャート要素の実際の x 座標（左）を指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。読み取り **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | チャートの左上隅を基準としたチャート要素の実際の上位置を指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。読み取り **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 下端。読み取り専用 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 親チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | タイトルの塗り、線、効果スタイルを返します。読み取り専用 [IFormat](../iformat/)。 |
| **float** [get_Height](./get_height/)() override | タイトルの高さをチャートの高さの比率で返します。読み取り **float**。 |
| **bool** [get_Overlay](./get_overlay/)() override | 他のチャート要素がタイトルと重なることを許可するかどうかを決定します。読み取り **bool**。 |
| **float** [get_Right](./get_right/)() override | 右端。読み取り専用 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | テキストフォーマットを返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | リッチフォーマットテキストを含めることができます。このプロパティが null でない場合、このフォーマットテキストの値は自動生成テキストを上書きします。自動生成テキストはデータラベル、値軸の表示単位ラベル、軸タイトル、チャートタイトル、トレンドラインのラベルの暗黙的プロパティです。自動生成テキストは [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) プロパティでフォーマットされます。読み取り専用 [ITextFrame](../../aspose.slides/itextframe/)。 |
| **float** [get_Width](./get_width/)() override | タイトルの幅をチャートの幅の比率で返します。読み取り **float**。 |
| **float** [get_X](./get_x/)() override | タイトルの x 座標をチャートの幅の比率で返します。読み取り **float**。 |
| **float** [get_Y](./get_y/)() override | タイトルの y 座標をチャートの高さの比率で返します。読み取り **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| void [set_Height](./set_height/)(**float**) override | タイトルの高さをチャートの高さの比率で設定します。書き込み **float**。 |
| void [set_Overlay](./set_overlay/)(**bool**) override | 他のチャート要素がタイトルと重なることを許可するかどうかを決定します。書き込み **bool**。 |
| void [set_Width](./set_width/)(**float**) override | タイトルの幅をチャートの幅の比率で設定します。書き込み **float**。 |
| void [set_X](./set_x/)(**float**) override | タイトルの x 座標をチャートの幅の比率で設定します。書き込み **float**。 |
| void [set_Y](./set_y/)(**float**) override | タイトルの y 座標をチャートの高さの比率で設定します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、返します。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウンタをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウンタをデクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IChartTitle](../icharttitle/)
* クラス [IDOMObject](../../aspose.slides/idomobject/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)