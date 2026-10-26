---
title: IChartPortionFormat
second_title: Aspose.Slides for C++ API リファレンス
description: チャートで使用されるチャート部分の書式設定プロパティを表します。
type: docs
weight: 807
url: /ja/aspose.slides.charts/ichartportionformat/
---
## IChartPortionFormat クラス

チャートで使用されるチャート部分の書式設定プロパティを表します。

```cpp
class IChartPortionFormat : public virtual Aspose::Slides::IBasePortionFormat
```

## メソッド

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/get_alternativelanguageid/)() | 代替言語の Id を返します。参照 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/ibaseportionformat/get_complexscriptfont/)() | 複合スクリプトフォント情報を返します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。参照 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/ibaseportionformat/get_eastasianfont/)() | 東アジアフォント情報を返します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。参照 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ibaseportionformat/get_effectformat/)() | テキスト [EffectFormat](../../aspose.slides/effectformat/) のプロパティを返します。継承は適用されません。読み取り専用 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| virtual **float** [get_Escapement](../../aspose.slides/ibaseportionformat/get_escapement/)() | 上付きまたは下付きテキストを返します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ibaseportionformat/get_fillformat/)() | テキスト [FillFormat](../../aspose.slides/fillformat/) のプロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/ibaseportionformat/get_fontbold/)() | フォントが太字かどうかを判定します。継承は適用されません。読み取り [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_FontHeight](../../aspose.slides/ibaseportionformat/get_fontheight/)() | 部分のフォント高さを返します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承すべきことを意味します。読み取り **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/ibaseportionformat/get_fontitalic/)() | フォントがイタリックかどうかを判定します。継承は適用されません。読み取り [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/ibaseportionformat/get_fontunderline/)() | テキストの下線タイプを返します。継承は適用されません。読み取り [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/ibaseportionformat/get_highlightcolor/)() | テキストのハイライトに使用される色を返します。継承は適用されません。読み取り専用 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/get_ishardunderlinefill/)() | 下線スタイルが独自の [FillFormat](../../aspose.slides/fillformat/) プロパティを持つか、テキストの [FillFormat](../../aspose.slides/fillformat/) プロパティから継承するかを判定します。読み取り [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/get_ishardunderlineline/)() | 下線スタイルが独自の [LineFormat](../../aspose.slides/lineformat/) プロパティを持つか、テキストの [LineFormat](../../aspose.slides/lineformat/) プロパティから継承するかを判定します。読み取り [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_KerningMinimalSize](../../aspose.slides/ibaseportionformat/get_kerningminimalsize/)() | カーニングを有効にすべき最小フォントサイズを返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。読み取り **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/ibaseportionformat/get_kumimoji/)() | 数値がテキストの東アジア固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。読み取り [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/ibaseportionformat/get_languageid/)() | 校正言語の Id を返します。スペルチェックと文法チェックに使用されます。読み取り [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/ibaseportionformat/get_latinfont/)() | ラテンフォント情報を返します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。読み取り [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ibaseportionformat/get_lineformat/)() | テキスト輪郭化のための [LineFormat](../../aspose.slides/lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/ibaseportionformat/get_normaliseheight/)() | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。読み取り [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/ibaseportionformat/get_proofdisabled/)() | テキストを校正しないかどうかを判定します。継承は適用されません。読み取り [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_Spacing](../../aspose.slides/ibaseportionformat/get_spacing/)() | 文字間スペースの増分を返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。読み取り **float**。 |
| virtual **bool** [get_SpellCheck](../../aspose.slides/ibaseportionformat/get_spellcheck/)() | テキスト部分のスペルチェックが有効かどうかを示す値を取得します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。デフォルト値は **false** です。 |
| virtual [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/ibaseportionformat/get_strikethroughtype/)() | テキストの取り消し線タイプを返します。継承は適用されません。読み取り [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/ibaseportionformat/get_symbolfont/)() | シンボリックフォント情報を返します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。読み取り [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/ibaseportionformat/get_textcaptype/)() | テキストの大文字小文字変換タイプを返します。継承は適用されません。読み取り [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/ibaseportionformat/get_underlinefillformat/)() | 下線線 [FillFormat](../../aspose.slides/fillformat/) のプロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/ibaseportionformat/get_underlinelineformat/)() | [LineFormat](../../aspose.slides/lineformat/) のプロパティを返します（下線線を輪郭化するために使用）。継承は適用されません。読み取り専用 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | 代替言語の Id を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_ComplexScriptFont](../../aspose.slides/ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 複合スクリプトフォント情報を設定します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。書き込み [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_EastAsianFont](../../aspose.slides/ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 東アジアフォント情報を設定します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。書き込み [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_Escapement](../../aspose.slides/ibaseportionformat/set_escapement/)(**float**) | 上付きまたは下付きテキストを設定します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。書き込み **float**。 |
| virtual void [set_FontBold](../../aspose.slides/ibaseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) | フォントが太字かどうかを判定します。継承は適用されません。書き込み [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_FontHeight](../../aspose.slides/ibaseportionformat/set_fontheight/)(**float**) | 部分のフォント高さを設定します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承すべきことを意味します。書き込み **float**。 |
| virtual void [set_FontItalic](../../aspose.slides/ibaseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) | フォントがイタリックかどうかを判定します。継承は適用されません。書き込み [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_FontUnderline](../../aspose.slides/ibaseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) | テキストの下線タイプを設定します。継承は適用されません。書き込み [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| virtual void [set_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) | 下線スタイルが独自の [FillFormat](../../aspose.slides/fillformat/) プロパティを持つか、テキストの [FillFormat](../../aspose.slides/fillformat/) プロパティから継承するかを判定します。書き込み [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) | 下線スタイルが独自の [LineFormat](../../aspose.slides/lineformat/) プロパティを持つか、テキストの [LineFormat](../../aspose.slides/lineformat/) プロパティから継承するかを判定します。書き込み [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_KerningMinimalSize](../../aspose.slides/ibaseportionformat/set_kerningminimalsize/)(**float**) | カーニングを有効にすべき最小フォントサイズを設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。書き込み **float**。 |
| virtual void [set_Kumimoji](../../aspose.slides/ibaseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) | 数値がテキストの東アジア固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。書き込み [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_LanguageId](../../aspose.slides/ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | 校正言語の Id を設定します。スペルチェックと文法チェックに使用されます。書き込み [System::String](../../system/string/)。 |
| virtual void [set_LatinFont](../../aspose.slides/ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | ラテンフォント情報を設定します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。書き込み [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_NormaliseHeight](../../aspose.slides/ibaseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。書き込み [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_ProofDisabled](../../aspose.slides/ibaseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) | テキストを校正しないかどうかを判定します。継承は適用されません。書き込み [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_Spacing](../../aspose.slides/ibaseportionformat/set_spacing/)(**float**) | 文字間スペースの増分を設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。書き込み **float**。 |
| virtual void [set_SpellCheck](../../aspose.slides/ibaseportionformat/set_spellcheck/)(**bool**) | テキスト部分のスペルチェックが有効かどうかを示す値を設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。デフォルト値は **false** です。 |
| virtual void [set_StrikethroughType](../../aspose.slides/ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) | テキストの取り消し線タイプを設定します。継承は適用されません。書き込み [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| virtual void [set_SymbolFont](../../aspose.slides/ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | シンボリックフォント情報を設定します。Null はフォントが未定義であり、マスターから継承すべきことを意味します。書き込み [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_TextCapType](../../aspose.slides/ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) | テキストの大文字化タイプを設定します。継承は適用されません。書き込み [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IBasePortionFormat](../../aspose.slides/ibaseportionformat/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)