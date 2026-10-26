---
title: IPictureFillFormat
second_title: Aspose.Slides for C++ API リファレンス
description: 画像塗りつぶしスタイルを表します。
type: docs
weight: 3225
url: /ja/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat クラス


画像塗りつぶしスタイルを表します。

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | 画像を、シェイプサイズと指定された解像度に基づいてサイズを縮小することで圧縮します。オプションで、切り取られた領域も削除します。 |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | 画像を、シェイプサイズと指定された解像度に基づいてサイズを縮小することで圧縮します。オプションで、切り取られた領域も削除します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | 塗りつぶし [Picture](../picture/) の切り取られた領域を削除します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | 画像の実際の高さのうち、下部が切り取られたパーセンテージ数を返します。読み取り **float**。 |
| virtual **float** [get_CropLeft](./get_cropleft/)() | 画像の実際の幅のうち、左側が切り取られたパーセンテージ数を返します。読み取り **float**。 |
| virtual **float** [get_CropRight](./get_cropright/)() | 画像の実際の幅のうち、右側が切り取られたパーセンテージ数を返します。読み取り **float**。 |
| virtual **float** [get_CropTop](./get_croptop/)() | 画像の実際の高さのうち、上部が切り取られたパーセンテージ数を返します。読み取り **float**。 |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | 画像の塗りつぶしに使用される DPI を返します。読み取り **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | 画像を返します。読み取り専用 [ISlidesPicture](../islidespicture/)。 |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | 画像塗りつぶしモードを返します。読み取り [Slides::PictureFillMode](../picturefillmode/)。 |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | シェイプのバウンディングボックスの下端からのパーセンテージオフセットで定義された塗りつぶし矩形の下端を返します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。読み取り **float**。 |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義された塗りつぶし矩形の左端を返します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。読み取り **float**。 |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | シェイプのバウンディングボックスの右端からのパーセンテージオフセットで定義された塗りつぶし矩形の右端を返します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。読み取り **float**。 |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義された塗りつぶし矩形の上端を返します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。読み取り **float**。 |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | テクスチャがシェイプ内でどのように配置されるかを返します。この設定はテクスチャパターンの開始点とシェイプ全体での繰り返し方法を制御します。読み取り [RectangleAlignment](../rectanglealignment/)。 |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | テクスチャタイルを水平、垂直、または両方の軸で反転します。読み取り [Slides::TileFlip](../tileflip/)。 |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | テクスチャの水平オフセット（ポイント単位）をシェイプの原点から返します。正の値はテクスチャを右に、負の値は左に移動させます。読み取り **float**。 |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | テクスチャの垂直オフセット（ポイント単位）をシェイプの原点から返します。正の値はテクスチャを下に、負の値は上に移動させます。読み取り **float**。 |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | テクスチャ塗りつぶしの水平スケールをパーセンテージで返します。読み取り **float**。 |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | テクスチャ塗りつぶしの垂直スケールをパーセンテージで返します。読み取り **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。本当に何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。本当に何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | 画像の実際の高さのうち、下部が切り取られたパーセンテージを設定します。書き込み **float**。 |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | 画像の実際の幅のうち、左側が切り取られたパーセンテージを設定します。書き込み **float**。 |
| virtual void [set_CropRight](./set_cropright/)(**float**) | 画像の実際の幅のうち、右側が切り取られたパーセンテージを設定します。書き込み **float**。 |
| virtual void [set_CropTop](./set_croptop/)(**float**) | 画像の実際の高さのうち、上部が切り取られたパーセンテージを設定します。書き込み **float**。 |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | 画像の塗りつぶしに使用される DPI を設定します。書き込み **int32_t**。 |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | 画像塗りつぶしモードを設定します。書き込み [Slides::PictureFillMode](../picturefillmode/)。 |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | シェイプのバウンディングボックスの下端からのパーセンテージオフセットで定義された塗りつぶし矩形の下端を設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。書き込み **float**。 |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義された塗りつぶし矩形の左端を設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。書き込み **float**。 |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | シェイプのバウンディングボックスの右端からのパーセンテージオフセットで定義された塗りつぶし矩形の右端を設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。書き込み **float**。 |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義された塗りつぶし矩形の上端を設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。書き込み **float**。 |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | テクスチャがシェイプ内でどのように配置されるかを設定します。この設定はテクスチャパターンの開始点とシェイプ全体での繰り返し方法を制御します。書き込み [RectangleAlignment](../rectanglealignment/)。 |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | テクスチャタイルを水平、垂直、または両方の軸で反転します。書き込み [Slides::TileFlip](../tileflip/)。 |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | テクスチャの水平オフセット（ポイント単位）をシェイプの原点から設定します。正の値はテクスチャを右に、負の値は左に移動させます。書き込み **float**。 |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | テクスチャの垂直オフセット（ポイント単位）をシェイプの原点から設定します。正の値はテクスチャを下に、負の値は上に移動させます。書き込み **float**。 |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | テクスチャ塗りつぶしの水平スケールをパーセンテージで設定します。書き込み **float**。 |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | テクスチャ塗りつぶしの垂直スケールをパーセンテージで設定します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | テンプレート引数 n 番目を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IFillParamSource](../ifillparamsource/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)