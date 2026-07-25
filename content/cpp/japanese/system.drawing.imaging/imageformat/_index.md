---
title: ImageFormat
second_title: Aspose.Slides for C++ API リファレンス
description: "画像のファイル形式を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。"
type: docs
weight: 131
url: /ja/system.drawing.imaging/imageformat/
---
## ImageFormat クラス

画像のファイル形式を表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。

```cpp
class ImageFormat : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | 現在のオブジェクトと指定されたオブジェクトが表す画像フォーマットが等しいかどうかを判定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートし、IEC 60559:1989 に従い NaN はどの値とも等しくないと規定されているにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートし、IEC 60559:1989 に従い NaN はどの値とも等しくないと規定されているにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | ビットマップ画像フォーマットを表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | 拡張メタファイルフォーマットを表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | Exchangeable [Image](../../system.drawing/image/) File (Exif) フォーマットを表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | [Graphics](../../system.drawing/graphics/) Interchange Format (GIF) 画像フォーマットを表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | 現在のオブジェクトが表す画像フォーマットに関連付けられた GUID を返します。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | [Windows](../../system.windows/) アイコン画像フォーマットを表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | Joint Photographic Experts Group (JPEG) 画像フォーマットを表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | メモリ内のビットマップ形式を表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG) 画像フォーマットを表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | Tagged [Image](../../system.drawing/image/) File Format (TIFF) 画像フォーマットを表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | [Windows](../../system.windows/) メタファイル (WMF) 画像フォーマットを表す [ImageFormat](./) オブジェクトへの共有ポインタを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似で、カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | 指定された GUID に関連付けられた画像フォーマットを表す [ImageFormat](./) クラスのインスタンスを構築します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似で、カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 参照比較で値型オブジェクトを nullptr と比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインタではなく弱ポインタに設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | この [ImageFormat](./) オブジェクトを人間が読める文字列に変換します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Drawing::Imaging](../)
* ライブラリ [Aspose.Slides](../../)