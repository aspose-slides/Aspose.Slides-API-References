---
title: Bitmap
second_title: Aspose.Slides for C++ API リファレンス
description: "GDI+ ビットマップ画像を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として使用してください。"
type: docs
weight: 1
url: /ja/system.drawing/bitmap/
---
## Bitmap クラス

GDI+ ビットマップ画像を表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用します。

```cpp
class Bitmap : public System::Drawing::Image
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | ピクセル処理モードを有効にします。 |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | 指定された既存の画像から新しい [Bitmap](./) オブジェクトを構築します。 |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | 指定されたストリームから新しい [Bitmap](./) オブジェクトを構築します。 |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | 指定されたファイルから新しい [Bitmap](./) オブジェクトを構築します。 |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | 指定されたファイルから新しい [Bitmap](./) オブジェクトを構築します。 |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | 指定された幅、高さ、ピクセルフォーマット、ピクセルデータを持つビットマップ画像を表す新しい [Bitmap](./) オブジェクトを構築します。 |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | 指定された既存の画像から、指定サイズにスケーリングされた新しい [Bitmap](./) オブジェクトを構築します。 |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | 指定された既存の画像から、幅と高さが指定された値にスケーリングされた新しい [Bitmap](./) オブジェクトを構築します。 |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | 現在のオブジェクトのコピーを作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | 現在のオブジェクトが表すビットマップ画像の領域のコピーを表す [Bitmap](./) オブジェクトを作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | 現在のオブジェクトが表すビットマップ画像の領域のコピーを表す [Bitmap](./) オブジェクトを作成します。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | SHA1 ハッシュ値を計算します。 |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | 指定されたビットマップ画像のコピーを作成し、ピクセルフォーマットを Format32bppArgb に変更します。 |
| void [Dispose](../image/dispose/)() override | 現在のオブジェクトが取得したすべてのリソースを解放します。 |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | ピクセル処理モードを無効にします。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | 指定されたファイルから [Image](../image/) オブジェクトを作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | 指定された GDI ビットマップから [Bitmap](./) オブジェクトを構築します。 |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | 指定されたストリームから [Image](../image/) オブジェクトを作成します。 |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | 画像の属性を表す ImageFlags 列挙値のビット単位の組み合わせを返します。 |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | 現在のオブジェクトが表す画像内のフレームの次元を表す GUID の配列を返します。 |
| int [get_Height](./get_height/)() const override | 画像の高さ（ピクセル単位）を返します。 |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | 現在のオブジェクトが表す画像の水平解像度（ピクセル/インチ）を返します。 |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | 現在のオブジェクトが表す画像で使用されているカラーパレットを返します。 |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | 現在のオブジェクトが表す画像のピクセルフォーマットを返します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | この画像に格納されているプロパティ項目の ID を取得します。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | この画像に格納されているすべてのプロパティ項目（メタデータ）を取得します。 |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | 現在のオブジェクトが表す画像のファイル形式を返します。 |
| [Size](../size/) [get_Size](../image/get_size/)() const | 画像の幅と高さ（ピクセル単位）を表す [Size](../size/) オブジェクトを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | 画像に関する追加データを提供するオブジェクトを取得します。 |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | 現在のオブジェクトが表す画像の垂直解像度（ピクセル/インチ）を返します。 |
| int [get_Width](./get_width/)() const override | 画像の幅（ピクセル単位）を返します。 |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | 指定された測定単位で画像の境界を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | 指定されたフレーム次元のフレーム数を返します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| IntPtr [GetHbitmap](./gethbitmap/)() | 現在のオブジェクトが表すビットマップから GDI ビットマップオブジェクトを作成します。 |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | 指定されたピクセルの色を返します。 |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | 指定されたピクセルフォーマットで色深度を表すのに使用されるビット数を返します。 |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | 基礎となる SkBitmap オブジェクトへの生ポインタを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | この [System::Drawing::Image](../image/) オブジェクトのサムネイルを取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子のアナログです。 |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | 指定されたピクセルフォーマットがアルファ情報を含むかどうかを判定します。 |
| **bool** [IsMultiImage](./ismultiimage/)() const override | 元のフォーマットがマルチイメージかどうかを返します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | [Bitmap](./) をシステムメモリにロックします。 |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | [Bitmap](./) をシステムメモリにロックします。 |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | 指定された色のすべてのピクセルの色を透明に変更します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| void [PremultipleColors](./premultiplecolors/)() | 現在のオブジェクトが表す画像のピクセルの色を事前乗算します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | 画像を 90 度の倍数で回転し、反転させます。 |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | 現在のオブジェクトが表す画像を PNG 形式で指定されたファイルに保存します。 |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | 現在のオブジェクトが表す画像を、指定された形式で指定されたファイルに保存します。 |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | 現在のオブジェクトが表す画像を、指定された形式で指定されたストリームに保存します。 |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | 現在のオブジェクトが表す画像を、指定されたエンコーダーとエンコーダーパラメータを使用して指定されたファイルに保存します。 |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | 現在のオブジェクトが表す画像を、指定されたエンコーダーとエンコーダーパラメータを使用して指定されたストリームに保存します。 |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](../image/save/) メソッドの前回の呼び出しで指定されたファイルまたはストリームにフレームを追加します。 |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](../image/save/) メソッドの前回の呼び出しで指定されたファイルまたはストリームにフレームを追加します。 |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | 指定されたフレームを選択します。 |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | 現在のオブジェクトが表す画像で使用されるカラーパレットを設定します。 |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 画像に関する追加データを提供するオブジェクトを設定します。 |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | 現在のオブジェクトが表すビットマップ画像の指定されたピクセルの色を設定します。 |
| void [SetResolution](./setresolution/)(**float**, **float**) | 画像の解像度を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタに設定します（shared ではなく）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | 指定されたビットマップのシステムメモリからのロックを解除します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Image](../image/)
* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)