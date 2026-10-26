---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API リファレンス
description: スライドのコンテンツを EMF ファイルとして保存します。
type: docs
weight: 170
url: /ja/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) メソッド

スライドのコンテンツを EMF ファイルとして保存します。

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 対象ストリーム |
## 備考

以下のコード例は、PowerPoint プレゼンテーションの最初のスライドをメタファイルに変換する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// 最初のスライドをメタファイルとして保存します
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [Slide](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)