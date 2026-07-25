---
title: get_InkEffectImages()
second_title: Aspose.Slides for C++ API リファレンス
description: インクブラシの視覚効果をシミュレートするために使用されるカスタム画像のコレクションを取得します。これらの画像は、Galaxy、Rainbow などの特定の InkEffectType 値でインクをレンダリングする際に使用されます。独自の画像を提供することで、各インク効果の表示方法を制御できます。
type: docs
weight: 14
url: /ja/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() メソッド


インクブラシの視覚効果をシミュレートするために使用されるカスタム画像のコレクションを取得します。これらの画像は、Galaxy、Rainbow などの特定の [InkEffectType](../../inkeffecttype/) 値でインクをレンダリングするときに使用されます。独自の画像を提供することで、各インク効果の表示方法を制御できます。

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## 備考


このプロパティにより、デフォルトのインク効果テクスチャをユーザー定義のものに置き換えることができ、ライセンスで制限されている場合や実行時にデフォルトアセットが利用できない場合に特に有用です。

辞書の各エントリは、[InkEffectType](../../inkeffecttype/) 値を対応する [IImage](../../../aspose.slides/iimage/) オブジェクト（例: Bitmap、または **Aspose** 画像インターフェイス）と関連付ける必要があります。

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## 参照

* 列挙型 [InkEffectType](../../inkeffecttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IDictionary](../../../system.collections.generic/idictionary/)
* クラス [IImage](../../../aspose.slides/iimage/)
* クラス [Ink](../)
* 名前空間 [Aspose::Slides::Ink](../../)
* ライブラリ [Aspose.Slides](../../../)