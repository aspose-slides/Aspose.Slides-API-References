---
title: IBasePortionFormat
second_title: Aspose.Slides for C++ API リファレンス
description: このクラスはテキスト部分の書式設定プロパティを含みます。IPortionFormatEffectiveData とは異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 1457
url: /ja/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat クラス


このクラスはテキスト部分の書式設定プロパティを含みます。[IPortionFormatEffectiveData](../iportionformateffectivedata/) とは異なり、このクラスのすべてのプロパティは書き込み可能です。

```cpp
class IBasePortionFormat : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | 代替言語の Id を返します。[System::String](../../system/string/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | 複雑スクリプトフォント情報を返します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。[IFontData](../ifontdata/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | 東アジアフォント情報を返します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。[IFontData](../ifontdata/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | テキスト [EffectFormat](../effectformat/) プロパティを返します。継承は適用されません。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| virtual **float** [get_Escapement](./get_escapement/)() | 上付きまたは下付きテキストを返します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。読み取りは **float** です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | テキスト [FillFormat](../fillformat/) プロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../ifillformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | フォントが太字かどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| virtual **float** [get_FontHeight](./get_fontheight/)() | 部分のフォント高さを返します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承されるべきことを意味します。読み取りは **float** です。 |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | フォントがイタリックかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | テキストの下線タイプを返します。継承は適用されません。[TextUnderlineType](../textunderlinetype/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | テキストのハイライトに使用される色を返します。継承は適用されません。読み取り専用 [IColorFormat](../icolorformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | 下線スタイルが独自の [FillFormat](../fillformat/) プロパティを持つか、テキストの [FillFormat](../fillformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) を参照してください。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | 下線スタイルが独自の [LineFormat](../lineformat/) プロパティを持つか、テキストの [LineFormat](../lineformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) を参照してください。 |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | カーニングを有効にすべき最小フォントサイズを返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。読み取りは **float** です。 |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | 数字がテキストの東アジア言語特有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | 校正言語の Id を返します。スペルチェックと文法チェックに使用されます。[System::String](../../system/string/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | ラテンフォント情報を返します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。[IFontData](../ifontdata/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | テキストアウトライン用の [LineFormat](../lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../ilineformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | テキストが校正対象でないかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) を参照してください。 |
| virtual **float** [get_Spacing](./get_spacing/)() | 文字間隔の増分を返します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。読み取りは **float** です。 |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | テキスト部分に対してスペルチェックが有効かどうかを示す値を取得します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定されている場合、スペルチェックが許可されます。デフォルト値は **false** です。 |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | テキストの取り消し線タイプを返します。継承は適用されません。[TextStrikethroughType](../textstrikethroughtype/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | シンボリックフォント情報を返します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。[IFontData](../ifontdata/) を参照してください。 |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | テキストの大文字化タイプを返します。継承は適用されません。[Slides::TextCapType](../textcaptype/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | 下線ライン [FillFormat](../fillformat/) プロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | 下線ラインのアウトラインに使用される [LineFormat](../lineformat/) プロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドに相当します。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しに相当します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子に相当します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | 代替言語の Id を設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 複雑スクリプトフォント情報を設定します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。[IFontData](../ifontdata/) に書き込みます。 |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 東アジアフォント情報を設定します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。[IFontData](../ifontdata/) に書き込みます。 |
| virtual void [set_Escapement](./set_escapement/)(**float**) | 上付きまたは下付きテキストを設定します。値は -100%（下付き）から 100%（上付き）です。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。**float** に書き込みます。 |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | フォントが太字かどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | 部分のフォント高さを設定します。**std::numeric_limits<float>::quiet_NaN()** は高さが未定義であり、マスターから継承されるべきことを意味します。**float** に書き込みます。 |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | フォントがイタリックかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | テキストの下線タイプを設定します。継承は適用されません。[TextUnderlineType](../textunderlinetype/) に書き込みます。 |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | 下線スタイルが独自の [FillFormat](../fillformat/) プロパティを持つか、テキストの [FillFormat](../fillformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | 下線スタイルが独自の [LineFormat](../lineformat/) プロパティを持つか、テキストの [LineFormat](../lineformat/) プロパティから継承するかを判定します。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | カーニングを有効にすべき最小フォントサイズを設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。**float** に書き込みます。 |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | 数字がテキストの東アジア言語特有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | 校正言語の Id を設定します。スペルチェックと文法チェックに使用されます。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ラテンフォント情報を設定します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。[IFontData](../ifontdata/) に書き込みます。 |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | テキストが校正対象でないかどうかを判定します。継承は適用されません。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_Spacing](./set_spacing/)(**float**) | 文字間隔の増分を設定します。**std::numeric_limits<float>::quiet_NaN()** は値が未定義であり、マスターから継承されるべきことを意味します。**float** に書き込みます。 |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | テキスト部分に対してスペルチェックが有効かどうかを示す値を設定します。このプロパティが false に設定された場合、テキスト要素のスペルチェックは抑制されます。true に設定された場合、スペルチェックが許可されます。デフォルト値は **false** です。 |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | テキストの取り消し線タイプを設定します。継承は適用されません。[TextStrikethroughType](../textstrikethroughtype/) に書き込みます。 |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | シンボリックフォント情報を設定します。Null はフォントが未定義であり、マスターから継承されるべきことを意味します。[IFontData](../ifontdata/) に書き込みます。 |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | テキストの大文字化タイプを設定します。継承は適用されません。[Slides::TextCapType](../textcaptype/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドに相当します。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

このクラスは特定の部分に定義されたテキスト部分の書式設定プロパティを取得および操作するために使用されます。つまり、値を取得する際に継承は適用されず、ほとんどの場合「未定義」を意味する値が取得されます。

継承を含む有効な書式設定パラメータの値を取得するには、[IPortionFormat::GetEffective](../iportionformat/geteffective/) メソッドを使用してください。このメソッドは [IPortionFormatEffectiveData](../iportionformateffectivedata/) インスタンスを返します。

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)