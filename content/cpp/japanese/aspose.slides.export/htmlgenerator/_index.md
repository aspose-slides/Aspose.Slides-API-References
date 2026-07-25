---
title: HtmlGenerator
second_title: Aspose.Slides for C++ API リファレンス
description: HTMLジェネレータ。
type: docs
weight: 105
url: /ja/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator クラス

Htmlジェネレータ。

```cpp
class HtmlGenerator : public Aspose::Slides::Export::IHtmlGenerator
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [AddAttributeValue](./addattributevalue/)([System::String](../../system/string/)) override | 属性値を引用し、htmlファイルに追加します。 |
| void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | 属性値を引用し、htmlファイルに追加します。 |
| void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 属性値を引用し、htmlファイルに追加します。 |
| void [AddHtml](./addhtml/)([System::String](../../system/string/)) override | フォーマットされたHTMLテキストを追加します。 |
| void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | フォーマットされたHTMLテキストを追加します。 |
| void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | フォーマットされたHTMLテキストを追加します。 |
| void [AddText](./addtext/)([System::String](../../system/string/)) override | htmlファイルにプレーンテキストを追加し、特殊文字をhtmlエンティティに置き換えます。改行や空白は置き換えられません。 |
| void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | htmlファイルにプレーンテキストを追加し、特殊文字をhtmlエンティティに置き換えます。改行や空白は置き換えられません。 |
| void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | htmlファイルにプレーンテキストを追加し、特殊文字をhtmlエンティティに置き換えます。改行や空白は置き換えられません。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN はどの値とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN はどの値とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **int32_t** [get_NextSlideIndex](./get_nextslideindex/)() override | 現在のスライドの次にレンダリングされるスライドのインデックス、または最後のスライドをレンダリング中の場合は -1 を返します。読み取り専用 **int32_t**。 |
| **int32_t** [get_PreviousSlideIndex](./get_previousslideindex/)() override | 以前にレンダリングされたスライドのインデックス、または最初のスライドがレンダリング中の場合は -1 を返します。読み取り専用 **int32_t**。 |
| [System::Drawing::SizeF](../../system.drawing/sizef/) [get_SlideImageSize](./get_slideimagesize/)() override | スライド画像のサイズを返します。読み取り専用 [System::Drawing::SizeF](../../system.drawing/sizef/)。 |
| [SvgCoordinateUnit](../svgcoordinateunit/) [get_SlideImageSizeUnit](./get_slideimagesizeunit/)() override | スライド画像サイズが指定される単位を返します。読み取り専用 [SvgCoordinateUnit](../svgcoordinateunit/)。 |
| [System::String](../../system/string/) [get_SlideImageSizeUnitCode](./get_slideimagesizeunitcode/)() override | スライド画像サイズが指定される単位の CSS コードを返します。読み取り専用 [System::String](../../system/string/)。 |
| **int32_t** [get_SlideIndex](./get_slideindex/)() override | 現在レンダリング中のスライドのインデックスを返します。読み取り専用 **int32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ではなく弱参照ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 参照

* クラス [IHtmlGenerator](../ihtmlgenerator/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)