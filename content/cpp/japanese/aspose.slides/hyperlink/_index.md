---
title: Hyperlink
second_title: Aspose.Slides for C++ API リファレンス
description: ハイパーリンクを表します。
type: docs
weight: 1236
url: /ja/aspose.slides/hyperlink/
---
## Hyperlink クラス

Represents a hyperlink.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 2 つの [Hyperlink](./) インスタンスが等しいかどうかを判断します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | [Hyperlink](./) のアクションの型を返します。読み取り専用 [HyperlinkActionType](../hyperlinkactiontype/)。 |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | ハイパーリンクの色のソースを表します（スタイルまたは部分フォーマット）。読み取り [HyperlinkColorSource](../hyperlinkcolorsource/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | ショーを終了するハイパーリンクを返します。読み取り専用 [Hyperlink](./)。 |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | 外部 URL を指定します。読み取り専用 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | この部分の実際の内容に関係なく、この部分に設定されたハイパーリンクを表します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | プレゼンテーションの最初のスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](./)。 |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | クリック時にハイパーリンクをハイライト表示すべきかどうかを判断します。読み取り **bool**。 |
| **bool** [get_History](./get_history/)() override | 呼び出されたときに、親ハイパーリンクのターゲットが閲覧済みハイパーリンクのリストに追加されるかどうかを判断します。読み取り **bool**。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | プレゼンテーションの最後のスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | 最後に閲覧したスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | 特殊な "play mediafile" ハイパーリンクを返します。[AudioFrame](../audioframe/) と [VideoFrame](../videoframe/) で使用されます。読み取り専用 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | 次のスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | 特殊な "do nothing" ハイパーリンクを返します。読み取り専用 [Hyperlink](./)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | 前のスライドへのハイパーリンクを返します。読み取り専用 [Hyperlink](./)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | ハイパーリンクの再生音を表します。読み取り [IAudio](../iaudio/)。 |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | ハイパーリンクのクリック時にサウンドを停止すべきかどうかを判断します。読み取り **bool**。 |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | 親ハイパーリンクのターゲットが存在する場合、親 HTML フレームセット内のフレームを返します。読み取り/書き込み [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | [Hyperlink](./) が特定のスライドを対象としている場合、そのスライドを返します。読み取り専用 [ISlide](../islide/)。 |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | 親ハイパーリンクに関連付けられ、ユーザーインターフェイスに表示される可能性のある文字列を返します。読み取り [System::String](../../system/string/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 特定の型に対するハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルなどのデータ構造で使用できます。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
|  [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | ハイパーリンクのインスタンスを作成します。 |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | 特定のスライドを指すハイパーリンクのインスタンスを作成します。注意: 作成されたハイパーリンクは同じプレゼンテーション内のオブジェクトに割り当てる必要があり、そうでない場合リンクは NoAction として保存されます。 |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | 別のハイパーリンクをソースとして使用し、二次プロパティを上書きしたハイパーリンクのインスタンスを作成します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照によって比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照によって比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列の場合に対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | ハイパーリンクの色のソース（スタイルまたは部分フォーマット）を表します。書き込み [HyperlinkColorSource](../hyperlinkcolorsource/)。 |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | クリック時にハイパーリンクをハイライト表示すべきかどうかを判断します。書き込み **bool**。 |
| void [set_History](./set_history/)(**bool**) override | 呼び出されたときに、親ハイパーリンクのターゲットが閲覧済みハイパーリンクのリストに追加されるかどうかを判断します。書き込み **bool**。 |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | ハイパーリンクの再生音を表します。書き込み [IAudio](../iaudio/)。 |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | ハイパーリンクのクリック時にサウンドを停止すべきかどうかを判断します。書き込み **bool**。 |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | 親ハイパーリンクのターゲットが存在する場合、親 HTML フレームセット内のフレームを返します。読み取り/書き込み [System::String](../../system/string/)。 |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | 親ハイパーリンクに関連付けられ、ユーザーインターフェイスに表示される可能性のある文字列を返します。書き込み [System::String](../../system/string/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させ、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [PVIObject](../pviobject/)
* クラス [IHyperlink](../ihyperlink/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)