---
title: get_RawFrame()
second_title: Aspose.Slides の C++ API リファレンス
description: 生のシェイプフレームのプロパティを返します。IShapeFrame を参照してください。
type: docs
weight: 40
url: /ja/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() メソッド


生のシェイプフレームのプロパティを返します。[IShapeFrame](../../ishapeframe/) を参照してください。

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## 備考


[IShape::set_Frame](../../ishape/set_frame/) に未定義のフレームを割り当てようとするコードは、一般的なケースでは意味がありません（特に、親 [GroupShape](../../groupshape/) が他の GroupShape に複数入れ子になっている場合）。例えば： 
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
このようなコードは不明瞭な状況を引き起こす可能性があります。[IShape::set_Frame](../../ishape/set_frame/) に未定義の値を使用することに対して制限が追加されました。x、y、width、height、flipH、flipV、rotationAngle の値は定義されていなければなりません（std::numeric_limits<float>::quiet_NaN() や [NullableBool::NotDefined](../../nullablebool/) ではない）。上記の例コードは現在 ArgumentException 例外をスローします。これは以下の使用例に適用されます： 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // 未定義にできません

SharedPtr<IShapeCollection> shapes = ...;
// x、y、width、height パラメータは std::numeric_limits<float>::quiet_NaN() にできません:
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


しかし、[IShape::set_RawFrame](../../ishape/set_rawframe/) メソッドのフレームは未定義である可能性があります。これはシェイプがプレースホルダーにリンクされている場合に意味があります。その場合、未定義のシェイプフレーム値は親プレースホルダーシェイプから上書きされます。そのシェイプに親プレースホルダーシェイプが存在しない場合、シェイプは [IShape::get_RawFrame](../../ishape/get_rawframe/) に基づいて有効フレームを評価する際にデフォルト値を使用します。x、y、width、height、flipH、flipV、rotationAngle のデフォルト値は 0 と [NullableBool::False](../../nullablebool/) です。例えば： 
```cpp
SharedPtr<IShape> shape = ...; // shape はプレースホルダーにリンクされています
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // この時 shape はプレースホルダーから x、y、height、flipH、flipV の値を継承し、width=100 と rotationAngle=0 を上書きします。
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IShapeFrame](../../ishapeframe/)
* クラス [Shape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)