---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API リファレンス
description: SVG 画像を EMF ファイルとして保存します。
type: docs
weight: 66
url: /ja/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) メソッド


SVG 画像を EMF ファイルとして保存します。

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 対象ストリーム |
## 備考



次の例は、SVG 画像をメタファイルに保存する方法を示しています。 
```cpp
// 新しい SVG 画像を作成します
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// SVG 画像をメタファイルとして保存します
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 このサンプルは、SVG 画像をメタファイルとしてプレゼンテーションの画像コレクションに追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新しい SVG 画像を作成します
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// SVG 画像をメタファイルとして保存します
svgImage->WriteAsEmf(memStream);
// メタファイルを画像コレクションに追加します
pres->get_Images()->AddImage(memStream->ToArray());
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [SvgImage](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)