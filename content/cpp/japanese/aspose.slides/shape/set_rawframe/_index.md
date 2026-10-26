---
title: set_RawFrame()
second_title: Aspose.Slides C++ 用 API リファレンス
description: 生のシェイプフレームのプロパティを設定します。IShapeFrame を書き込みます。
type: docs
weight: 53
url: /ja/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) メソッド

生のシェイプフレームのプロパティを設定します。[IShapeFrame](../../ishapeframe/) を書き込みます。

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## 備考

未定義のフレームを [IShape::set_Frame](../../ishape/set_frame/) に割り当てようとするコードは、一般的なケースでは意味がありません（特に、親 [GroupShape](../../groupshape/) が他の GroupShape に複数入れ子になっている場合）。例として： 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 または 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 このようなコードは不明瞭な状況を招く可能性があります。そのため、[IShape::set_Frame](../../ishape/set_frame/) に未定義の値を使用することに制限が追加されました。x、y、width、height、flipH、flipV、rotationAngle の値は定義されていなければなりません（std::numeric_limits<float>::quiet_NaN() または [NullableBool::NotDefined](../../nullablebool/) ではない）。上記の例コードは現在 ArgumentException 例外をスローします。これは以下の使用例に適用されます： 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // 未定義にできません

SharedPtr<IShapeCollection> shapes = ...;
// x、y、width、height パラメータは std::numeric_limits<float>::quiet_NaN() であってはなりません:
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```

ただし、[IShape::set_RawFrame](../../ishape/set_rawframe/) メソッドのフレームは未定義でも構いません。これは、シェイプがプレースホルダーにリンクされている場合に意味があります。その場合、未定義のシェイプフレームの値は親プレースホルダーシェイプから上書きされます。シェイプに親プレースホルダーシェイプが存在しない場合、そのシェイプは [IShape::get_RawFrame](../../ishape/get_rawframe/) に基づいて実効フレームを評価する際にデフォルト値を使用します。デフォルト値は x、y、width、height、flipH、flipV、rotationAngle に対して 0 と [NullableBool::False](../../nullablebool/) です。例として： 
```cpp
SharedPtr<IShape> shape = ...; // shape はプレースホルダーにリンクされています
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // これで shape はプレースホルダーから x、y、height、flipH、flipV の値を継承し、width=100 と rotationAngle=0 を上書きします。
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IShapeFrame](../../ishapeframe/)
* クラス [Shape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)