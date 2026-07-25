---
title: AddOleObjectFrame()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 66
url: /ja/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) メソッド

新しいOLEオブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいOLEフレームのx座標（ポイント）。 |
| y | **float** | 新しいOLEフレームのy座標（ポイント）。 |
| width | **float** | 新しいOLEフレームの幅（ポイント）。 |
| height | **float** | 新しいOLEフレームの高さ（ポイント）。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 埋め込みOLEデータ情報（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 戻り値

新しく作成された[IOleObjectFrame](../../ioleobjectframe/)。

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) メソッド

新しいOLEオブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいOLEフレームのx座標（ポイント）。 |
| y | **float** | 新しいOLEフレームのy座標（ポイント）。 |
| width | **float** | 新しいOLEフレームの幅（ポイント）。 |
| height | **float** | 新しいOLEフレームの高さ（ポイント）。 |
| className | [System::String](../../../system/string/) | OLEオブジェクトのクラス名。 |
| path | [System::String](../../../system/string/) | リンクされたファイルへのパス。 |

### 戻り値

新しく作成された[IOleObjectFrame](../../ioleobjectframe/)。

## 備考

このパスはプレゼンテーション内にそのまま保存されます。相対パスが指定された場合、別のディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IOleObjectFrame](../../ioleobjectframe/)
* クラス [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* クラス [IShapeCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)