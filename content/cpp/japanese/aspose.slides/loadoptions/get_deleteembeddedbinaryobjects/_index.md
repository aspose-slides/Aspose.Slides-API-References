---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションの読み込み中に Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを判定します。
type: docs
weight: 339
url: /ja/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() メソッド


[Aspose.Slides](../../) がプレゼンテーションの読み込み中にすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## 備考


埋め込みバイナリオブジェクトのタイプ:

* VBA プロジェクト [IPresentation::VbaProject](../)
* OLE オブジェクト埋め込みデータ [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) バイナリ データ [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


**bool** を読み取ります。

既定は **false** です。

以下の例は、埋め込みバイナリオブジェクトなしでプレゼンテーションを読み込む方法を示します。
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## 参照

* クラス [LoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)