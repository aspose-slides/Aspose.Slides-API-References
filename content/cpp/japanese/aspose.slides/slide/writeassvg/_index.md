---
title: WriteAsSvg()
second_title: Aspose.Slides for C++ API リファレンス
description: スライドの内容を SVG ファイルとして保存します。
type: docs
weight: 157
url: /ja/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) メソッド

スライドの内容を SVG ファイルとして保存します。

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 対象ストリーム |
## 備考

以下のコード例は、PowerPoint プレゼンテーションの最初のスライドを SVG ファイルに変換する方法を示しています。  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// 最初のスライドを SVG ファイルとして保存します
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) メソッド

スライドの内容を SVG ファイルとして保存します。

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 対象ストリーム |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG 生成オプション |
## 備考

以下のコード例は、PowerPoint プレゼンテーションの最初のスライドをオプション付きで SVG ファイルに変換する方法を示しています。  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// 最初のスライドを SVG ファイルとして保存します
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [Slide](../)
* クラス [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)