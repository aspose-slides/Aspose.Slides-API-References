---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API リファレンス
description: SVG イメージを EMF ファイルとして保存します。
type: docs
weight: 53
url: /ja/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) メソッド

SVG イメージを EMF ファイルとして保存します。

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 対象ストリーム |
## 備考

次の例は、SVG イメージをメタファイルに保存する方法を示しています。 
```cpp
// 新しい SVG 画像を作成します
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// SVG 画像をメタファイルとして保存します
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
このサンプルは、SVG イメージをメタファイルとしてプレゼンテーションの画像コレクションに追加する方法を示します。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新しい SVG 画像を作成します
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// メタファイルとして SVG 画像を保存します
svgImage->WriteAsEmf(memStream);
// メタファイルを画像コレクションに追加します
pres->get_Images()->AddImage(memStream->ToArray());
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [ISvgImage](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)