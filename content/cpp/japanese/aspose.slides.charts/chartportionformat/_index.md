---
title: ChartPortionFormat
second_title: Aspose.Slides for C++ API リファレンス
description: このクラスは、チャートで使用されるチャート部分の書式設定プロパティを含みます。IPortionFormatEffectiveData とは異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 261
url: /ja/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat クラス


このクラスは、チャートで使用されるチャート部分の書式設定プロパティを含みます。[IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/)とは異なり、このクラスのすべてのプロパティは書き込み可能です。

```cpp
class ChartPortionFormat : public Aspose::Slides::BasePortionFormat,
                           public Aspose::Slides::Charts::IChartPortionFormat
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにも関わらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにも関わらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/baseportionformat/get_alternativelanguageid/)() override | 代替言語の Id を返します。[System::String](../../system/string/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/baseportionformat/get_complexscriptfont/)() override | 複合スクリプトのフォント情報を返します。null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../../aspose.slides/ifontdata/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/baseportionformat/get_eastasianfont/)() override | 東アジアフォント情報を返します。null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../../aspose.slides/ifontdata/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/baseportionformat/get_effectformat/)() override | テキスト [EffectFormat](../../aspose.slides/effectformat/) プロパティを返します。継承は適用されません。読み取り専用 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| **float** [get_Escapement](../../aspose.slides/baseportionformat/get_escapement/)() override | 上付きまたは下付きテキストを返します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/baseportionformat/get_fillformat/)() override | テキスト [FillFormat](../../aspose.slides/fillformat/) プロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/baseportionformat/get_fontbold/)() override | フォントが太字かどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) を読み取ります。 |
| **float** [get_FontHeight](../../aspose.slides/baseportionformat/get_fontheight/)() override | 部分のフォント高さを返します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承すべきことを意味します。**float** を読み取ります。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/baseportionformat/get_fontitalic/)() override | フォントがイタリックかどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) を読み取ります。 |
| [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/baseportionformat/get_fontunderline/)() override | テキスト下線タイプを返します。継承は適用されません。[TextUnderlineType](../../aspose.slides/textunderlinetype/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/baseportionformat/get_highlightcolor/)() override | テキストのハイライトに使用される色を返します。継承は適用されません。読み取り専用 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/baseportionformat/get_ishardunderlinefill/)() override | 下線スタイルが独自の [FillFormat](../../aspose.slides/fillformat/) プロパティを持つか、テキストの [FillFormat](../../aspose.slides/fillformat/) プロパティから継承するかを判定します。[NullableBool](../../aspose.slides/nullablebool/) を読み取ります。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/baseportionformat/get_ishardunderlineline/)() override | 下線スタイルが独自の [LineFormat](../../aspose.slides/lineformat/) プロパティを持つか、テキストの [LineFormat](../../aspose.slides/lineformat/) プロパティから継承するかを判定します。[NullableBool](../../aspose.slides/nullablebool/) を読み取ります。 |
| **float** [get_KerningMinimalSize](../../aspose.slides/baseportionformat/get_kerningminimalsize/)() override | カーニングを有効にすべき最小フォントサイズを返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** を読み取ります。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/baseportionformat/get_kumimoji/)() override | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) を読み取ります。 |
| [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/baseportionformat/get_languageid/)() override | 校正言語の Id を返します。スペルチェックと文法チェックに使用されます。[System::String](../../system/string/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/baseportionformat/get_latinfont/)() override | ラテンフォント情報を返します。null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../../aspose.slides/ifontdata/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/baseportionformat/get_lineformat/)() override | テキストアウトライン用の [LineFormat](../../aspose.slides/lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/baseportionformat/get_normaliseheight/)() override | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) を読み取ります。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../../aspose.slides/idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/baseportionformat/get_proofdisabled/)() override | テキストが校正されるべきでないかどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) を読み取ります。 |
| **float** [get_Spacing](../../aspose.slides/baseportionformat/get_spacing/)() override | 文字間隔増分を返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** を読み取ります。 |
| **bool** [get_SpellCheck](../../aspose.slides/baseportionformat/get_spellcheck/)() override | テキスト部分に対してスペルチェックが有効かどうかを示す値を取得します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。既定値は **false** です。 |
| [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/baseportionformat/get_strikethroughtype/)() override | テキストの取り消し線タイプを返します。継承は適用されません。[TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/baseportionformat/get_symbolfont/)() override | シンボリックフォント情報を返します。null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../../aspose.slides/ifontdata/) を読み取ります。 |
| [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/baseportionformat/get_textcaptype/)() override | テキストの大文字化タイプを返します。継承は適用されません。[Slides::TextCapType](../../aspose.slides/textcaptype/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/baseportionformat/get_underlinefillformat/)() override | 下線ライン [FillFormat](../../aspose.slides/fillformat/) プロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/baseportionformat/get_underlinelineformat/)() override | 下線ラインをアウトラインするために使用される [LineFormat](../../aspose.slides/lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_AlternativeLanguageId](../../aspose.slides/baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | 代替言語の Id を設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_ComplexScriptFont](../../aspose.slides/baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 複合スクリプトのフォント情報を設定します。null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../../aspose.slides/ifontdata/) に書き込みます。 |
| void [set_EastAsianFont](../../aspose.slides/baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 東アジアフォント情報を設定します。null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../../aspose.slides/ifontdata/) に書き込みます。 |
| void [set_Escapement](../../aspose.slides/baseportionformat/set_escapement/)(**float**) override | 上付きまたは下付きテキストを設定します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** に書き込みます。 |
| void [set_FontBold](../../aspose.slides/baseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) override | フォントが太字かどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) に書き込みます。 |
| void [set_FontHeight](../../aspose.slides/baseportionformat/set_fontheight/)(**float**) override | 部分のフォント高さを設定します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承すべきことを意味します。**float** に書き込みます。 |
| void [set_FontItalic](../../aspose.slides/baseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) override | フォントがイタリックかどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) に書き込みます。 |
| void [set_FontUnderline](../../aspose.slides/baseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) override | テキスト下線タイプを設定します。継承は適用されません。[TextUnderlineType](../../aspose.slides/textunderlinetype/) に書き込みます。 |
| void [set_IsHardUnderlineFill](../../aspose.slides/baseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) override | 下線スタイルが独自の [FillFormat](../../aspose.slides/fillformat/) プロパティを持つか、テキストの [FillFormat](../../aspose.slides/fillformat/) プロパティから継承するかを判定します。[NullableBool](../../aspose.slides/nullablebool/) に書き込みます。 |
| void [set_IsHardUnderlineLine](../../aspose.slides/baseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) override | 下線スタイルが独自の [LineFormat](../../aspose.slides/lineformat/) プロパティを持つか、テキストの [LineFormat](../../aspose.slides/lineformat/) プロパティから継承するかを判定します。[NullableBool](../../aspose.slides/nullablebool/) に書き込みます。 |
| void [set_KerningMinimalSize](../../aspose.slides/baseportionformat/set_kerningminimalsize/)(**float**) override | カーニングを有効にすべき最小フォントサイズを設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** に書き込みます。 |
| void [set_Kumimoji](../../aspose.slides/baseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) override | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) に書き込みます。 |
| void [set_LanguageId](../../aspose.slides/baseportionformat/set_languageid/)([System::String](../../system/string/)) override | 校正言語の Id を設定します。スペルチェックと文法チェックに使用されます。[System::String](../../system/string/) に書き込みます。 |
| void [set_LatinFont](../../aspose.slides/baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | ラテンフォント情報を設定します。null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../../aspose.slides/ifontdata/) に書き込みます。 |
| void [set_NormaliseHeight](../../aspose.slides/baseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) override | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) に書き込みます。 |
| void [set_ProofDisabled](../../aspose.slides/baseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) override | テキストが校正されるべきでないかどうかを判定します。継承は適用されません。[NullableBool](../../aspose.slides/nullablebool/) に書き込みます。 |
| void [set_Spacing](../../aspose.slides/baseportionformat/set_spacing/)(**float**) override | 文字間隔増分を設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承すべきことを意味します。**float** に書き込みます。 |
| void [set_SpellCheck](../../aspose.slides/baseportionformat/set_spellcheck/)(**bool**) override | テキスト部分に対してスペルチェックが有効かどうかを示す値を設定します。プロパティが false に設定された場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。既定値は **false** です。 |
| void [set_StrikethroughType](../../aspose.slides/baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) override | テキストの取り消し線タイプを設定します。継承は適用されません。[TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) に書き込みます。 |
| void [set_SymbolFont](../../aspose.slides/baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | シンボリックフォント情報を設定します。null はフォントが未定義であり、マスターから継承すべきことを意味します。[IFontData](../../aspose.slides/ifontdata/) に書き込みます。 |
| void [set_TextCapType](../../aspose.slides/baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) override | テキストの大文字化タイプを設定します。継承は適用されません。[Slides::TextCapType](../../aspose.slides/textcaptype/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考


このクラスは、特定の部分に対して定義されたテキスト部分の書式設定プロパティを取得および操作するために使用されます。これは、値を取得する際に継承が適用されないことを意味し、ほとんどの場合「未定義」という意味の値が取得されます。

継承を含む有効な書式設定パラメータの値を取得するには、[PortionFormat::GetEffective](../../aspose.slides/portionformat/geteffective/) メソッドを使用し、[IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/) インスタンスを返します。

## 参照

* クラス [BasePortionFormat](../../aspose.slides/baseportionformat/)
* クラス [IChartPortionFormat](../ichartportionformat/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)