---
title: AddGroupShape()
second_title: Aspose.Slides の C++ API リファレンス
description: 新しい空のグループ シェイプを作成し、シェイプ コレクションの末尾に追加します。グループのフレームは、追加されたシェイプに合わせて自動的に調整されます。
type: docs
weight: 391
url: /ja/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() メソッド

新しい空のグループ シェイプを作成し、シェイプ コレクションの末尾に追加します。グループのフレームは、追加されたシェイプに合わせて自動的に調整されます。

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### 戻り値

新しく作成された[IGroupShape](../../igroupshape/)です。

## 備考

次の例は、PowerPoint [Presentation](../../presentation/) のスライドにグループ シェイプを追加する方法を示しています。

```cpp
// Presentation クラスのインスタンス化
auto pres = System::MakeObject<Presentation>();

// 最初のスライドを取得
auto slide = pres->get_Slides()->idx_get(0);
// スライドのシェイプ コレクションにアクセス
auto slideShapes = slide->get_Shapes();
// スライドにグループ シェイプを追加
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// 追加したグループ シェイプ内にシェイプを追加
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// グループ シェイプのフレームを追加
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// PPTX ファイルをディスクに書き込む
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) メソッド

新しいグループ シェイプを作成し、指定された SVG 画像を個々のシェイプに変換し、結果として得られたグループをシェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) はベクトル コンテンツを含み、シェイプに変換されます。 |
| x | **float** | ポイント単位のグループのフレームの x 座標です。 |
| y | **float** | ポイント単位のグループのフレームの y 座標です。 |
| width | **float** | ポイント単位のグループのフレームの幅です。 |
| height | **float** | ポイント単位のグループのフレームの高さです。 |

### 戻り値

新しく作成された[IGroupShape](../../igroupshape/)です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IGroupShape](../../igroupshape/)
* クラス [ShapeCollection](../)
* クラス [ISvgImage](../../isvgimage/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)