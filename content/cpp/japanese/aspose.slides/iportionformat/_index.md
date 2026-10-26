---
title: IPortionFormat
second_title: Aspose.Slides for C++ API リファレンス
description: このクラスはテキスト部分の書式設定プロパティを含みます。IPortionFormatEffectiveDataとは異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 3329
url: /ja/aspose.slides/iportionformat/
---
## IPortionFormat クラス

このクラスはテキスト部分の書式設定プロパティを含みます。[IPortionFormatEffectiveData](../iportionformateffectivedata/) とは異なり、このクラスのすべてのプロパティは書き込み可能です。

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | 代替言語の ID を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | ブックマーク識別子を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | 複合スクリプトフォント情報を返します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。読み取り [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | 東アジアフォント情報を返します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。読み取り [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | [EffectFormat](../effectformat/) テキストプロパティを返します。継承は適用されません。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | 上付きまたは下付きテキストを返します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | テキスト [FillFormat](../fillformat/) プロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../ifillformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | フォントが太字かどうかを判定します。継承は適用されません。読み取り [NullableBool](../nullablebool/)。 |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | 部分のフォント高さを返します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承されるべきことを意味します。読み取り **float**。 |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | フォントがイタリックかどうかを判定します。継承は適用されません。読み取り [NullableBool](../nullablebool/)。 |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | テキストの下線タイプを返します。継承は適用されません。読み取り [TextUnderlineType](../textunderlinetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | テキストのハイライトに使用される色を返します。継承は適用されません。読み取り専用 [IColorFormat](../icolorformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | マウスクリック用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ハイパーリンクマネージャー 読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | マウスオーバー用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../ihyperlink/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | 下線スタイルが独自の [FillFormat](../fillformat/) プロパティを持つか、テキストの [FillFormat](../fillformat/) プロパティから継承されるかを判定します。読み取り [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | 下線スタイルが独自の [LineFormat](../lineformat/) プロパティを持つか、テキストの [LineFormat](../lineformat/) プロパティから継承されるかを判定します。読み取り [NullableBool](../nullablebool/)。 |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | カーニングを有効にすべき最小フォントサイズを返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。読み取り **float**。 |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | 数字がテキストの東方言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。読み取り [NullableBool](../nullablebool/)。 |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | 校正言語の ID を返します。スペルチェックと文法チェックに使用されます。読み取り [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | ラテンフォント情報を返します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。読み取り [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | テキスト輪郭用の [LineFormat](../lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../ilineformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。読み取り [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | テキストを校正しないかどうかを判定します。継承は適用されません。読み取り [NullableBool](../nullablebool/)。 |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | スマートタグをクリーンアップすべきかどうかを判定します。継承は適用されません。読み取り **bool**。 |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | 文字間スペース増分を返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。読み取り **float**。 |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | テキスト部分のスペルチェックが有効かどうかを示す値を取得します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。デフォルト値は **false** です。 |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | テキストの取り消し線タイプを返します。継承は適用されません。読み取り [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | 記号フォント情報を返します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。読み取り [IFontData](../ifontdata/)。 |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | テキストの大文字化タイプを返します。継承は適用されません。読み取り [Slides::TextCapType](../textcaptype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | 下線ライン [FillFormat](../fillformat/) プロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | 下線ラインの輪郭に使用される [LineFormat](../lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | 継承が適用された有効な部分書式データを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述される型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | 代替言語の ID を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | ブックマーク識別子を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 複合スクリプトフォント情報を設定します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。書き込み [IFontData](../ifontdata/)。 |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 東アジアフォント情報を設定します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。書き込み [IFontData](../ifontdata/)。 |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | 上付きまたは下付きテキストを設定します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。書き込み **float**。 |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | フォントが太字かどうかを判定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | 部分のフォント高さを設定します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承されるべきことを意味します。書き込み **float**。 |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | フォントがイタリックかどうかを判定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | テキストの下線タイプを設定します。継承は適用されません。書き込み [TextUnderlineType](../textunderlinetype/)。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | 下線スタイルが独自の [FillFormat](../fillformat/) プロパティを持つか、テキストの [FillFormat](../fillformat/) プロパティから継承されるかを判定します。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | 下線スタイルが独自の [LineFormat](../lineformat/) プロパティを持つか、テキストの [LineFormat](../lineformat/) プロパティから継承されるかを判定します。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | カーニングを有効にすべき最小フォントサイズを設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。書き込み **float**。 |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | 数字がテキストの東方言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | 校正言語の ID を設定します。スペルチェックと文法チェックに使用されます。書き込み [System::String](../../system/string/)。 |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ラテンフォント情報を設定します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。書き込み [IFontData](../ifontdata/)。 |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | テキストを校正しないかどうかを判定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | スマートタグをクリーンアップすべきかどうかを判定します。継承は適用されません。書き込み **bool**。 |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | 文字間スペース増分を設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。書き込み **float**。 |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | テキスト部分のスペルチェックが有効かどうかを示す値を設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。デフォルト値は **false** です。 |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | テキストの取り消し線タイプを設定します。継承は適用されません。書き込み [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 記号フォント情報を設定します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。書き込み [IFontData](../ifontdata/)。 |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | テキストの大文字化タイプを設定します。継承は適用されません。書き込み [Slides::TextCapType](../textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列へ変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

このクラスは、特定の部分に対して定義されたテキスト部分の書式設定プロパティを返したり操作したりするために使用されます。これは、値を取得する際に継承が適用されないことを意味し、ほとんどの場合「未定義」の値が得られます。

継承を含む有効な書式パラメータ値を取得するには、[IPortionFormat::GetEffective](./geteffective/) メソッドを使用する必要があります。このメソッドは [IPortionFormatEffectiveData](../iportionformateffectivedata/) インスタンスを返します。

## 参照

* クラス [IBasePortionFormat](../ibaseportionformat/)
* クラス [IHyperlinkContainer](../ihyperlinkcontainer/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)