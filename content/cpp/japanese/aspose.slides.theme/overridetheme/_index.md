---
title: OverrideTheme
second_title: Aspose.Slides for C++ API リファレンス
description: オーバーライドテーマを表します。
type: docs
weight: 547
url: /ja/aspose.slides.theme/overridetheme/
---
## OverrideTheme クラス

オーバーライドテーマを表します。

```cpp
class OverrideTheme : public Aspose::Slides::Theme::Theme,
                      public Aspose::Slides::Theme::IOverrideTheme
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Clear](./clear/)() override | [ColorScheme](../colorscheme/)、[FontScheme](../fontscheme/)、[FormatScheme](../formatscheme/) を null に設定して、このテーマオブジェクトによるすべてのオーバーライドを無効にします。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいと見なします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいと見なします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](./get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](./get_colorscheme/)() override | カラースキームを返します。読み取り専用 [IColorScheme](../icolorscheme/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](./get_fontscheme/)() override | フォントスキームを返します。読み取り専用 [IFontScheme](../ifontscheme/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](./get_formatscheme/)() override | シェイプフォーマットスキームを返します。読み取り専用 [IFormatScheme](../iformatscheme/)。 |
| **bool** [get_IsEmpty](./get_isempty/)() override | true の場合、[ColorScheme](../colorscheme/)、[FontScheme](../fontscheme/)、[FormatScheme](../formatscheme/) が null であり、このテーマオブジェクトによるすべてのオーバーライドが無効になっていることを意味します。読み取り専用 **bool**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../theme/get_presentation/)() override | 親プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../theme/geteffective/)() override | 継承が適用された有効なテーマデータを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| void [InitColorScheme](./initcolorscheme/)() override | [ColorScheme](../colorscheme/) を新しいオブジェクトで初期化し、InheritedTheme の [ColorScheme](../colorscheme/) をオーバーライドします。 |
| void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) override | [ColorScheme](../colorscheme/) を新しいオブジェクトで初期化し、InheritedTheme の [ColorScheme](../colorscheme/) をオーバーライドします。 |
| void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() override | [ColorScheme](../colorscheme/) を新しいオブジェクトで初期化し、InheritedTheme の [ColorScheme](../colorscheme/) をオーバーライドします。また、この新しいオブジェクトのデータを InheritedTheme の [ColorScheme](../colorscheme/) のデータで初期化します。 |
| void [InitFontScheme](./initfontscheme/)() override | [FontScheme](../fontscheme/) を新しいオブジェクトで初期化し、InheritedTheme の [FontScheme](../fontscheme/) をオーバーライドします。 |
| void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) override | [FontScheme](../fontscheme/) を新しいオブジェクトで初期化し、InheritedTheme の [FontScheme](../fontscheme/) をオーバーライドします。 |
| void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() override | [FontScheme](../fontscheme/) を新しいオブジェクトで初期化し、InheritedTheme の [FontScheme](../fontscheme/) をオーバーライドします。また、この新しいオブジェクトのデータを InheritedTheme の [FontScheme](../fontscheme/) のデータで初期化します。 |
| void [InitFormatScheme](./initformatscheme/)() override | [FormatScheme](../formatscheme/) を新しいオブジェクトで初期化し、InheritedTheme の [FormatScheme](../formatscheme/) をオーバーライドします。 |
| void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) override | [FormatScheme](../formatscheme/) を新しいオブジェクトで初期化し、InheritedTheme の [FormatScheme](../formatscheme/) をオーバーライドします。 |
| void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() override | [FormatScheme](../formatscheme/) を新しいオブジェクトで初期化し、InheritedTheme の [FormatScheme](../formatscheme/) をオーバーライドします。また、この新しいオブジェクトのデータを InheritedTheme の [FormatScheme](../formatscheme/) のデータで初期化します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Theme](../theme/)
* クラス [IOverrideTheme](../ioverridetheme/)
* 名前空間 [Aspose::Slides::Theme](../)
* ライブラリ [Aspose.Slides](../../)