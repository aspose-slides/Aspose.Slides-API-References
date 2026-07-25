---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスに新しい OLE オブジェクト フレームを作成し、シェイプ コレクションに挿入します。
type: docs
weight: 79
url: /ja/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) メソッド

新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | OLE オブジェクト フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい OLE フレームの幅（ポイント単位）。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント単位）。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 埋め込み OLE データ情報（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 戻り値

新しく作成された [IOleObjectFrame](../../ioleobjectframe/)。

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) メソッド

新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | OLE オブジェクト フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい OLE フレームの幅（ポイント単位）。 |
| height | **float** | 新しい OLE フレームの高さ（ポイント単位）。 |
| className | [System::String](../../../system/string/) | OLE オブジェクトのクラス名。 |
| path | [System::String](../../../system/string/) | リンクされたファイルへのパス。 |

### 戻り値

新しく作成された [IOleObjectFrame](../../ioleobjectframe/)。

## 備考

このパスはプレゼンテーションに文字通り保存されます。相対パスが指定された場合、別のディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IOleObjectFrame](../../ioleobjectframe/)
* クラス [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* クラス [IShapeCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)