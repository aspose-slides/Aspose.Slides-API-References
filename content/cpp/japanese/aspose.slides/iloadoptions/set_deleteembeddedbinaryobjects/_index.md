---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションの読み込み中に Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。
type: docs
weight: 352
url: /ja/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) メソッド

[Aspose.Slides](../../) がプレゼンテーションのロード中にすべての埋め込みバイナリ オブジェクトを削除するかどうかを決定します。

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## 備考

埋め込みバイナリ オブジェクトの種類:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

**bool** を書き込みます。

デフォルトは **false** です。

次の例は、埋め込みバイナリ オブジェクトなしでプレゼンテーションをロードする方法を示しています。
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## 参照

* クラス [ILoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)