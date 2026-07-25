---
title: AddConnector()
second_title: Aspose.Slides for C++ APIリファレンス
description: デフォルトのテンプレートスタイルを使用して新しいコネクタ形状を作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 417
url: /ja/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) メソッド

デフォルトのテンプレートスタイルを使用して新しいコネクタ形状を作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 追加するコネクタ形状の [ShapeType](../../shapetype/)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された [IConnector](../../iconnector/)。

## 備考

次の例は、PowerPoint [Presentation](../../presentation/) で 2 つのシェイプ（楕円と長方形）間にコネクタ（曲がったコネクタ）を追加する方法を示しています。

```cpp
// PPTX ファイルを表すプレゼンテーション クラスのインスタンスを作成します
auto input = System::MakeObject<Presentation>();

// 特定のスライドのシェイプ コレクションにアクセスします
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// 楕円のオートシェイプを追加します
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// 四角形のオートシェイプを追加します
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// スライドのシェイプ コレクションにコネクタ形状を追加します
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// コネクタを使用してシェイプを接続します
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// コネクタの再ルーティングを呼び出し、シェイプ間の自動最短パスを設定します
connector->Reroute();

// プレゼンテーションを保存します
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) メソッド

新しいコネクタ形状を作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルトのテンプレートスタイルを適用できます。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 作成するコネクタ形状の [ShapeType](../../shapetype/)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |
| createFromTemplate | **bool** | True の場合、デフォルトのテンプレートスタイル（名前が空でなく、シンプルなスタイル）を適用します。false の場合、デフォルトのプロパティ値でコネクタを作成します。 |

### 戻り値

新しく作成された [IConnector](../../iconnector/)。

## 参照

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)