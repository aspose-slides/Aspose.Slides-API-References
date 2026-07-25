---
title: BasePortionFormat
second_title: Aspose.Slides の C++ API リファレンス
description: テキスト部分の共通書式設定プロパティです。
type: docs
weight: 144
url: /ja/aspose.slides/baseportionformat/
---
## BasePortionFormat クラス

テキスト部分の共通書式設定プロパティです。

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## メソッド

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 自身も含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 自身も含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | 代替言語の ID を返します。[System::String](../../system/string/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | 複合スクリプトのフォント情報を返します。null はフォントが未定義であり、マスタから継承すべきことを意味します。[IFontData](../ifontdata/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | 東アジアフォント情報を返します。null はフォントが未定義であり、マスタから継承すべきことを意味します。[IFontData](../ifontdata/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | テキスト [EffectFormat](../effectformat/) プロパティを返します。継承は適用されません。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| **float** [get_Escapement](./get_escapement/)() override | 上付きまたは下付きテキストを返します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスタから継承すべきことを意味します。**float** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | テキスト [FillFormat](../fillformat/) プロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../ifillformat/)。 |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | フォントが太字かどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| **float** [get_FontHeight](./get_fontheight/)() override | 部分のフォント高さを返します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスタから継承すべきことを意味します。**float** を読み取ります。 |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | フォントがイタリックかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | テキストの下線タイプを返します。継承は適用されません。[TextUnderlineType](../textunderlinetype/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | テキストのハイライトに使用される色を返します。継承は適用されません。読み取り専用 [IColorFormat](../icolorformat/)。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | 下線スタイルが独自の [FillFormat](../fillformat/) プロパティを持つか、テキストの [FillFormat](../fillformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) を参照してください。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | 下線スタイルが独自の [LineFormat](../lineformat/) プロパティを持つか、テキストの [LineFormat](../lineformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) を参照してください。 |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | カーニングを有効にすべき最小フォントサイズを返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスタから継承すべきことを意味します。**float** を読み取ります。 |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | 数字がテキストの東方言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | 校正言語の ID を返します。スペルチェックと文法チェックに使用されます。[System::String](../../system/string/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | ラテンフォント情報を返します。null はフォントが未定義であり、マスタから継承すべきことを意味します。[IFontData](../ifontdata/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | テキストアウトライン用の [LineFormat](../lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../ilineformat/)。 |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | テキストが校正されるべきでないかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| **float** [get_Spacing](./get_spacing/)() override | 文字間隔の増分を返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスタから継承すべきことを意味します。**float** を読み取ります。 |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | テキスト部分に対してスペルチェックが有効かどうかを示す値を取得します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。既定値は **false** です。 |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | テキストの取り消し線タイプを返します。継承は適用されません。[TextStrikethroughType](../textstrikethroughtype/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | シンボリックフォント情報を返します。null はフォントが未定義であり、マスタから継承すべきことを意味します。[IFontData](../ifontdata/) を参照してください。 |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | テキストの大文字化タイプを返します。継承は適用されません。[Slides::TextCapType](../textcaptype/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | 下線ライン [FillFormat](../fillformat/) のプロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | 下線ラインをアウトラインするために使用される [LineFormat](../lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文によるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|   [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | 代替言語の ID を設定します。[System::String](../../system/string/) に書き込んでください。 |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 複合スクリプトのフォント情報を設定します。null はフォントが未定義であり、マスタから継承すべきことを意味します。[IFontData](../ifontdata/) に書き込んでください。 |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 東アジアフォント情報を設定します。null はフォントが未定義であり、マスタから継承すべきことを意味します。[IFontData](../ifontdata/) に書き込んでください。 |
| void [set_Escapement](./set_escapement/)(**float**) override | 上付きまたは下付きテキストを設定します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスタから継承すべきことを意味します。**float** に書き込んでください。 |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | フォントが太字かどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込んでください。 |
| void [set_FontHeight](./set_fontheight/)(**float**) override | 部分のフォント高さを設定します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスタから継承すべきことを意味します。**float** に書き込んでください。 |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | フォントがイタリックかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込んでください。 |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | テキストの下線タイプを設定します。継承は適用されません。[TextUnderlineType](../textunderlinetype/) に書き込んでください。 |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | 下線スタイルが独自の [FillFormat](../fillformat/) プロパティを持つか、テキストの [FillFormat](../fillformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) に書き込んでください。 |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | 下線スタイルが独自の [LineFormat](../lineformat/) プロパティを持つか、テキストの [LineFormat](../lineformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) に書き込んでください。 |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | カーニングを有効にすべき最小フォントサイズを設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスタから継承すべきことを意味します。**float** に書き込んでください。 |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | 数字がテキストの東方言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込んでください。 |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | 校正言語の ID を設定します。スペルチェックと文法チェックに使用されます。[System::String](../../system/string/) に書き込んでください。 |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | ラテンフォント情報を設定します。null はフォントが未定義であり、マスタから継承すべきことを意味します。[IFontData](../ifontdata/) に書き込んでください。 |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込んでください。 |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | テキストが校正されるべきでないかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込んでください。 |
| void [set_Spacing](./set_spacing/)(**float**) override | 文字間隔の増分を設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスタから継承すべきことを意味します。**float** に書き込んでください。 |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | テキスト部分でスペルチェックが有効かどうかを示す値を設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。既定値は **false** です。 |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | テキストの取り消し線タイプを設定します。継承は適用されません。[TextStrikethroughType](../textstrikethroughtype/) に書き込んでください。 |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | シンボリックフォント情報を設定します。null はフォントが未定義であり、マスタから継承すべきことを意味します。[IFontData](../ifontdata/) に書き込んでください。 |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | テキストの大文字化タイプを設定します。継承は適用されません。[Slides::TextCapType](../textcaptype/) に書き込んでください。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [PVIObject](../pviobject/)
* クラス [IBasePortionFormat](../ibaseportionformat/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)