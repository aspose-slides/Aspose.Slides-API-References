---
title: SetEmbeddedData()
second_title: C++ 用 Aspose.Slides API リファレンス
description: OLE 埋め込みデータに関する情報を設定します。
type: docs
weight: 248
url: /ja/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) メソッド

OLE 埋め込みデータに関する情報を設定します。

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 埋め込みデータ [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## 備考

このメソッドはオブジェクトのプロパティを新しいデータに合わせて変更し、IsObjectLink フラグを false に設定して、OLE オブジェクトが埋め込まれていることを示します。 

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* クラス [OleObjectFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)