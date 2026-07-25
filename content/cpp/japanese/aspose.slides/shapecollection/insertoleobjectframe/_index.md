---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。
type: docs
weight: 196
url: /ja/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) メソッド

新しい OLE オブジェクト フレームを作成し、指定されたインデックスに shape コレクションに挿入します。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | OLE オブジェクト フレームを挿入するゼロベースのインデックスです。 |
| x | **float** | 新しい OLE フレームの x 座標（ポイント単位）です。 |
| y | **float** | 新しい OLE フレームの y 座標（ポイント単位）です。 |
| width | **float** | 新しい OLE フレームの幅（ポイント単位）です。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント単位）です。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 埋め込まれた OLE データ情報（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 戻り値

新しく作成された [IOleObjectFrame](../../ioleobjectframe/)です。

## 備考



この例は、2 番目のインデックスに OLE オブジェクトを挿入する方法を示しています: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) メソッド

新しい OLE オブジェクト フレームを作成し、指定されたインデックスに shape コレクションに挿入します。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | OLE オブジェクト フレームを挿入するゼロベースのインデックスです。 |
| x | **float** | 新しい OLE フレームの x 座標（ポイント単位）です。 |
| y | **float** | 新しい OLE フレームの y 座標（ポイント単位）です。 |
| width | **float** | 新しい OLE フレームの幅（ポイント単位）です。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント単位）です。 |
| className | [System::String](../../../system/string/) | OLE オブジェクトのクラス名です。 |
| path | [System::String](../../../system/string/) | リンクされたファイルへのパスです。 |

### 戻り値

新しく作成された OLE オブジェクト フレームです。

## 備考



このパスはプレゼンテーションにそのまま保存されます。相対パスが指定された場合、別のディレクトリからプレゼンテーションを開く際にファイルにアクセスできなくなります。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IOleObjectFrame](../../ioleobjectframe/)
* クラス [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* クラス [ShapeCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)