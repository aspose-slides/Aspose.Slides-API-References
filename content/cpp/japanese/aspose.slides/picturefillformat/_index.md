---
title: PictureFillFormat
second_title: Aspose.Slides for C++ API リファレンス
description: 画像塗りつぶしスタイルを表します。
type: docs
weight: 4720
url: /ja/aspose.slides/picturefillformat/
---
## PictureFillFormat クラス

Represents a picture fill style.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | 画像をシェイプのサイズと指定された解像度に基づいてサイズを縮小して圧縮します。オプションで、切り取られた領域も削除します。 |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | 画像をシェイプのサイズと指定された解像度に基づいてサイズを縮小して圧縮します。オプションで、切り取られた領域も削除します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | 塗りつぶし [Picture](../picture/) の切り取られた領域を削除します。 |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| **float** [get_CropBottom](./get_cropbottom/)() override | 画像の実際の高さのうち、下部が切り取られたパーセンテージ数を返します。読み取り **float**。 |
| **float** [get_CropLeft](./get_cropleft/)() override | 画像の実際の幅のうち、左側が切り取られたパーセンテージ数を返します。読み取り **float**。 |
| **float** [get_CropRight](./get_cropright/)() override | 画像の実際の幅のうち、右側が切り取られたパーセンテージ数を返します。読み取り **float**。 |
| **float** [get_CropTop](./get_croptop/)() override | 画像の実際の高さのうち、上部が切り取られたパーセンテージ数を返します。読み取り **float**。 |
| **int32_t** [get_Dpi](./get_dpi/)() override | 画像の塗りつぶしに使用される DPI を返します。読み取り **int32_t**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | 画像を返します。読み取り専用 [ISlidesPicture](../islidespicture/)。 |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | 画像の塗りつぶしモードを返します。読み取り [Slides::PictureFillMode](../picturefillmode/)。 |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | シェイプのバウンディングボックスの底辺からのパーセンテージオフセットで定義された塗りつぶし矩形の底辺を返します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。読み取り **float**。 |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | シェイプのバウンディングボックスの左辺からのパーセンテージオフセットで定義された塗りつぶし矩形の左辺を返します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。読み取り **float**。 |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | シェイプのバウンディングボックスの右辺からのパーセンテージオフセットで定義された塗りつぶし矩形の右辺を返します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。読み取り **float**。 |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | シェイプのバウンディングボックスの上辺からのパーセンテージオフセットで定義された塗りつぶし矩形の上辺を返します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。読み取り **float**。 |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | テクスチャがシェイプ内でどのように配置されるかを返します。この設定はテクスチャパターンの開始点とシェイプ全体での繰り返し方法を制御します。読み取り [RectangleAlignment](../rectanglealignment/)。 |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | テクスチャタイルを水平、垂直、または両方の軸で反転します。読み取り [Slides::TileFlip](../tileflip/)。 |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | テクスチャのシェイプ原点からの水平オフセット（ポイント単位）を返します。正の値はテクスチャを右に、負の値は左に移動させます。読み取り **float**。 |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | テクスチャのシェイプ原点からの垂直オフセット（ポイント単位）を返します。正の値はテクスチャを下に、負の値は上に移動させます。読み取り **float**。 |
| **float** [get_TileScaleX](./get_tilescalex/)() override | テクスチャ塗りつぶしの水平スケール（パーセンテージ）を返します。読み取り **float**。 |
| **float** [get_TileScaleY](./get_tilescaley/)() override | テクスチャ塗りつぶしの垂直スケール（パーセンテージ）を返します。読み取り **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | 画像の実際の高さのうち、下部が切り取られたパーセンテージ数を設定します。書き込み **float**。 |
| void [set_CropLeft](./set_cropleft/)(**float**) override | 画像の実際の幅のうち、左側が切り取られたパーセンテージ数を設定します。書き込み **float**。 |
| void [set_CropRight](./set_cropright/)(**float**) override | 画像の実際の幅のうち、右側が切り取られたパーセンテージ数を設定します。書き込み **float**。 |
| void [set_CropTop](./set_croptop/)(**float**) override | 画像の実際の高さのうち、上部が切り取られたパーセンテージ数を設定します。書き込み **float**。 |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | 画像の塗りつぶしに使用される DPI を設定します。書き込み **int32_t**。 |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | 画像の塗りつぶしモードを設定します。書き込み [Slides::PictureFillMode](../picturefillmode/)。 |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | シェイプのバウンディングボックスの底辺からのパーセンテージオフセットで定義された塗りつぶし矩形の底辺を設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。書き込み **float**。 |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | シェイプのバウンディングボックスの左辺からのパーセンテージオフセットで定義された塗りつぶし矩形の左辺を設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。書き込み **float**。 |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | シェイプのバウンディングボックスの右辺からのパーセンテージオフセットで定義された塗りつぶし矩形の右辺を設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。書き込み **float**。 |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | シェイプのバウンディングボックスの上辺からのパーセンテージオフセットで定義された塗りつぶし矩形の上辺を設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを示します。書き込み **float**。 |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | テクスチャがシェイプ内でどのように配置されるかを設定します。この設定はテクスチャパターンの開始点とシェイプ全体での繰り返し方法を制御します。書き込み [RectangleAlignment](../rectanglealignment/)。 |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | テクスチャタイルを水平、垂直、または両方の軸で反転させます。書き込み [Slides::TileFlip](../tileflip/)。 |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | テクスチャのシェイプ原点からの水平オフセット（ポイント単位）を設定します。正の値はテクスチャを右に、負の値は左に移動させます。書き込み **float**。 |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | テクスチャのシェイプ原点からの垂直オフセット（ポイント単位）を設定します。正の値はテクスチャを下に、負の値は上に移動させます。書き込み **float**。 |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | テクスチャ塗りつぶしの水平スケール（パーセンテージ）を設定します。書き込み **float**。 |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | テクスチャ塗りつぶしの垂直スケール（パーセンテージ）を設定します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインタではなく弱ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [PVIObject](../pviobject/)
* クラス [IPictureFillFormat](../ipicturefillformat/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)