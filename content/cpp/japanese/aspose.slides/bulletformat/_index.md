---
title: BulletFormat
second_title: Aspose.Slides for C++ API リファレンス
description: 段落の弾丸書式プロパティを表します。
type: docs
weight: 248
url: /ja/aspose.slides/bulletformat/
---
## BulletFormat クラス

段落の弾丸書式プロパティを表します。

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | 弾丸が有効な場合、段落の Indent と MarginLeft に対して有効な非ゼロシフトをデフォルトで設定します（PowerPoint が段落の箇条書き/番号付けを有効にしたときと同様）。弾丸が無効な場合は、段落の Indent と MarginLeft をリセットします（PowerPoint が段落の箇条書き/番号付けを無効にしたときと同様）。インデントシフトは現在の弾丸コンテキスト（IBulletFormat::get(set)_Type、.NumberedBulletStyle、最初の部分の FontHeight）に基づいて適用されます。非ゼロのインデントシフトは現在の段落の有効な Indent と MarginLeft に適用され（結果の値がローカル値になります）。 |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| char16_t [get_Char](./get_char/)() override | 継承なしで段落の弾丸文字を返します。**wchar_t** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | 継承なしで段落の弾丸のカラー形式を返します。読み取り専用 [IColorFormat](../icolorformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | 継承なしで段落の弾丸フォントを返します。[IFontData](../ifontdata/) を読み取ります。 |
| **float** [get_Height](./get_height/)() override | 継承なしで段落の弾丸高さを返します。値 std::numeric_limits<float>::quiet_NaN() は、弾丸が段落の最初の部分から高さを継承することを示します。**float** を読み取ります。 |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | 弾丸が独自のカラーを持つか、段落の最初の部分から継承するかを判定します。弾丸が独自のカラーを持つ場合は **[NullableBool::True](../nullablebool/)**、段落の最初の部分からカラーを継承する場合は **[NullableBool::False](../nullablebool/)** です。[NullableBool](../nullablebool/) を読み取ります。 |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | 弾丸が独自のフォントを持つか、段落の最初の部分から継承するかを判定します。弾丸が独自のフォントを持つ場合は **[NullableBool::True](../nullablebool/)**、段落の最初の部分からフォントを継承する場合は **[NullableBool::False](../nullablebool/)** です。[NullableBool](../nullablebool/) を読み取ります。 |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | 継承なしで番号付き弾丸グループに使用される最初の番号を返します。**int16_t** を読み取ります。 |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | 継承なしで番号付き弾丸のスタイルを返します。[Slides::NumberedBulletStyle](../numberedbulletstyle/) を読み取ります。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | 継承なしで段落の弾丸として使用される画像を返します。読み取り専用 [ISlidesPicture](../islidespicture/)。 |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | 継承なしで段落の弾丸タイプを返します。[BulletType](../bullettype/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | 継承が適用された有効な弾丸書式データを取得します。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType によって記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースのための [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースのための [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Char](./set_char/)(char16_t) override | 継承なしで段落の弾丸文字を設定します。**wchar_t** を書き込みます。 |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 継承なしで段落の弾丸フォントを設定します。[IFontData](../ifontdata/) を書き込みます。 |
| void [set_Height](./set_height/)(**float**) override | 継承なしで段落の弾丸高さを設定します。値 std::numeric_limits<float>::quiet_NaN() は、弾丸が段落の最初の部分から高さを継承することを示します。**float** を書き込みます。 |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | 弾丸が独自のカラーを持つか、段落の最初の部分から継承するかを判定します。弾丸が独自のカラーを持つ場合は **[NullableBool::True](../nullablebool/)**、段落の最初の部分からカラーを継承する場合は **[NullableBool::False](../nullablebool/)** です。[NullableBool](../nullablebool/) を書き込みます。 |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | 弾丸が独自のフォントを持つか、段落の最初の部分から継承するかを判定します。弾丸が独自のフォントを持つ場合は **[NullableBool::True](../nullablebool/)**、段落の最初の部分からフォントを継承する場合は **[NullableBool::False](../nullablebool/)** です。[NullableBool](../nullablebool/) を書き込みます。 |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | 継承なしで番号付き弾丸グループに使用される最初の番号を設定します。**int16_t** を書き込みます。 |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | 継承なしで番号付き弾丸のスタイルを設定します。[Slides::NumberedBulletStyle](../numberedbulletstyle/) を書き込みます。 |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | 継承なしで段落の弾丸タイプを設定します。[BulletType](../bullettype/) を書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [PVIObject](../pviobject/)
* クラス [IBulletFormat](../ibulletformat/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)