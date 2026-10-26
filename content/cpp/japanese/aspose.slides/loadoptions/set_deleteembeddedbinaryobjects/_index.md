---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides C++ 用 API リファレンス
description: プレゼンテーションの読み込み時に、Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。
type: docs
weight: 352
url: /ja/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) メソッド

[Aspose.Slides](../../) がプレゼンテーションの読み込み中に埋め込みバイナリオブジェクトをすべて削除するかどうかを決定します。

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## 備考

* VBA Project [IPresentation::VbaProject](../)
* OLE Object 埋め込みデータ [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) バイナリデータ [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

書き込み **bool**。

既定は **false**。

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