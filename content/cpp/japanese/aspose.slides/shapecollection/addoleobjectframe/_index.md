---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ APIリファレンス
description: 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 183
url: /ja/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) メソッド

新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい OLE フレームの幅（ポイント単位）。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント単位）。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 埋め込まれた OLE データに関する情報（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 戻り値

新しく作成された [IOleObjectFrame](../../ioleobjectframe/)。

## 備考

次の例は、PowerPoint [Presentation](../../presentation/) の [Slides](../../) に OLE オブジェクト フレームを追加する方法を示しています。  
```cpp
auto pres = System::MakeObject<Presentation>();

// 最初のスライドにアクセスします
auto slide = pres->get_Slides()->idx_get(0);
// Excel ファイルをストリームにロードします
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// 埋め込み用のデータオブジェクトを作成します
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Ole Object Frame シェイプを追加します
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// PPTX ファイルをディスクに保存します
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) メソッド

新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい OLE フレームの幅（ポイント単位）。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント単位）。 |
| className | [System::String](../../../system/string/) | OLE オブジェクトのクラス名。 |
| path | [System::String](../../../system/string/) | リンクされたファイルへのパス。 |

### 戻り値

新しく作成された [IOleObjectFrame](../../ioleobjectframe/)。

## 備考

このパスはプレゼンテーション内にそのまま保存されます。相対パスが指定された場合、別のディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IOleObjectFrame](../../ioleobjectframe/)
* クラス [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* クラス [ShapeCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)