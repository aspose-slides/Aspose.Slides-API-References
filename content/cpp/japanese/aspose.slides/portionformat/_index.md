---
title: PortionFormat
second_title: Aspose.Slides for C++ API リファレンス
description: このクラスはテキスト部分の書式設定プロパティを含みます。IPortionFormatEffectiveData とは異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 4811
url: /ja/aspose.slides/portionformat/
---
## PortionFormat クラス

このクラスはテキスト部分の書式設定プロパティを含みます。[IPortionFormatEffectiveData](../iportionformateffectivedata/) とは異なり、このクラスのすべてのプロパティは書き込み可能です。

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 自身を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 自身を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用です。 |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | 代替言語の Id を返します。参照 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | ブックマーク識別子を返します。参照 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | 複雑スクリプトフォント情報を返します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。参照 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | 東アジアフォント情報を返します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。参照 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | テキスト [EffectFormat](../effectformat/) プロパティを返します。継承は適用されません。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | 上付きまたは下付きテキストを返します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | テキスト [FillFormat](../fillformat/) プロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../ifillformat/)。 |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | フォントが太字かどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照。 |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | 部分のフォント高さを返します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承すべきことを意味します。**float** を読み取ります。 |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | フォントが斜体かどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照。 |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | テキストの下線タイプを返します。継承は適用されません。[TextUnderlineType](../textunderlinetype/) を参照。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | テキストのハイライトに使用される色を返します。継承は適用されません。読み取り専用 [IColorFormat](../icolorformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | マウスクリック用に定義されたハイパーリンクを返します。[IHyperlink](../ihyperlink/) を参照。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | ハイパーリンクマネージャーです。読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | マウスオーバー用に定義されたハイパーリンクを返します。[IHyperlink](../ihyperlink/) を参照。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | 下線スタイルが独自の [FillFormat](../fillformat/) プロパティを持つか、テキストの [FillFormat](../fillformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) を参照。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | 下線スタイルが独自の [LineFormat](../lineformat/) プロパティを持つか、テキストの [LineFormat](../lineformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) を参照。 |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | カーニングをオンにすべき最小フォントサイズを返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** を読み取ります。 |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照。 |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | 校正言語の Id を返します。スペルと文法のチェックに使用されます。[System::String](../../system/string/) を参照。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | ラテンフォント情報を返します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../ifontdata/) を参照。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | テキストアウトライン用の [LineFormat](../lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../ilineformat/)。 |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | テキストが校正されるべきでないかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照。 |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | スマートタグをクリーンアップすべきかどうかを判定します。継承は適用されません。**bool** を読み取ります。 |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | 文字間スペーシングの増分を返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** を読み取ります。 |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | テキスト部分のスペルチェックが有効かどうかを示す値を取得します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定されている場合、スペルチェックが許可されます。デフォルト値は **false** です。 |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | テキストの取り消し線タイプを返します。継承は適用されません。[TextStrikethroughType](../textstrikethroughtype/) を参照。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | シンボリックフォント情報を返します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../ifontdata/) を参照。 |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | テキストの大文字化タイプを返します。継承は適用されません。[Slides::TextCapType](../textcaptype/) を参照。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | 下線ライン [FillFormat](../fillformat/) プロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | 下線ラインをアウトラインするために使用される [LineFormat](../lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | 継承が適用された有効な部分書式データを取得します。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローンを可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
|  [PortionFormat](./portionformat/)() | [PortionFormat](./) クラスの新しいインスタンスを初期化します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | 代替言語の Id を設定します。[System::String](../../system/string/) に書き込み。 |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | ブックマーク識別子を設定します。[System::String](../../system/string/) に書き込み。 |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 複雑スクリプトフォント情報を設定します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../ifontdata/) に書き込み。 |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 東アジアフォント情報を設定します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../ifontdata/) に書き込み。 |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | 上付きまたは下付きテキストを設定します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** に書き込み。 |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | フォントが太字かどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込み。 |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | 部分のフォント高さを設定します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承すべきことを意味します。**float** に書き込み。 |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | フォントが斜体かどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込み。 |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | テキストの下線タイプを設定します。継承は適用されません。[TextUnderlineType](../textunderlinetype/) に書き込み。 |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスクリック用に定義されたハイパーリンクを設定します。[IHyperlink](../ihyperlink/) に書き込み。 |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスオーバー用に定義されたハイパーリンクを設定します。[IHyperlink](../ihyperlink/) に書き込み。 |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | 下線スタイルが独自の [FillFormat](../fillformat/) プロパティを持つか、テキストの [FillFormat](../fillformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) に書き込み。 |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | 下線スタイルが独自の [LineFormat](../lineformat/) プロパティを持つか、テキストの [LineFormat](../lineformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) に書き込み。 |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | カーニングをオンにすべき最小フォントサイズを設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** に書き込み。 |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込み。 |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | 校正言語の Id を設定します。スペルと文法のチェックに使用されます。[System::String](../../system/string/) に書き込み。 |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | ラテンフォント情報を設定します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../ifontdata/) に書き込み。 |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込み。 |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | テキストが校正されるべきでないかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込み。 |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | スマートタグをクリーンアップすべきかどうかを判定します。継承は適用されません。**bool** に書き込み。 |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | 文字間スペーシングの増分を設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** に書き込み。 |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | テキスト部分のスペルチェックが有効かどうかを示す値を設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定されている場合、スペルチェックが許可されます。デフォルト値は **false** です。 |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | テキストの取り消し線タイプを設定します。継承は適用されません。[TextStrikethroughType](../textstrikethroughtype/) に書き込み。 |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | シンボリックフォント情報を設定します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../ifontdata/) に書き込み。 |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | テキストの大文字化タイプを設定します。継承は適用されません。[Slides::TextCapType](../textcaptype/) に書き込み。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、戻します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破壊します。すべての内部データ構造を解放します。 |

## 備考

このクラスは特定の部分に定義されたテキスト部分書式プロパティを返したり操作したりするために使用されます。つまり、値を取得するときに継承は適用されず、ほとんどの場合「未定義」を意味する値が取得されます。

継承を含む有効な書式パラメータ値を取得するには、[PortionFormat::GetEffective](./geteffective/) メソッドを使用してください。このメソッドは [IPortionFormatEffectiveData](../iportionformateffectivedata/) インスタンスを返します。

以下の例は、PowerPoint [Presentation](../presentation/) の [Paragraph](../paragraph/) の部分にラテンフォントを割り当てる方法を示しています。

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides はこれらの特別な識別子を使用します（PowerPoint で使用されるものに似ています）:
// +mn-lt - 本文フォント ラテン (マイナーフォント)
// +mj-lt -Heading フォント ラテン (メジャー ラテン フォント)
// +mn-ea - 本文フォント 東アジア (マイナ― 東アジア フォント)
// +mj-ea - Body フォント 東アジア (マイナ― 東アジア フォント)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## 参照

* クラス [BasePortionFormat](../baseportionformat/)
* クラス [IPortionFormat](../iportionformat/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)