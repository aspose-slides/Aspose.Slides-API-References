---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides の C++ API リファレンス
description: プレゼンテーションの読み込み中に、Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを判断します。
type: docs
weight: 339
url: /ja/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() メソッド


[Aspose.Slides](../../) がプレゼンテーションの読み込み中にすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## 備考


埋め込みバイナリオブジェクトの種類:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


**bool** を読み取ります。 

デフォルトは **false** です。 

以下の例は、埋め込みバイナリオブジェクトなしでプレゼンテーションを読み込む方法を示しています。 
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