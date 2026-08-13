---
title: set_RawFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 원시 쉐이프 프레임의 속성을 설정합니다. IShapeFrame을 씁니다.
type: docs
weight: 53
url: /ko/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) 메서드

원시 쉐이프 프레임의 속성을 설정합니다. [IShapeFrame](../../ishapeframe/)를 씁니다.

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## 비고

[IShape::set_Frame](../../ishape/set_frame/)에 정의되지 않은 프레임을 할당하려는 코드는 일반적인 경우에 의미가 없습니다(특히 부모 [GroupShape](../../groupshape/)가 다른 GroupShape에 여러 번 중첩된 경우). 예시:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
또는
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
이러한 코드는 불명확한 상황을 초래할 수 있습니다. 따라서 [IShape::set_Frame](../../ishape/set_frame/)에 정의되지 않은 값을 사용하는 것에 대한 제한이 추가되었습니다. x, y, width, height, flipH, flipV 및 rotationAngle 값은 정의되어야 합니다( std::numeric_limits<float>::quiet_NaN() 또는 [NullableBool::NotDefined](../../nullablebool/)가 아닌 경우). 위의 예제 코드는 이제 ArgumentException 예외를 발생시킵니다. 이는 다음 사용 사례에 적용됩니다:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // 정의될 수 없습니다

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height 매개변수는 std::numeric_limits<float>::quiet_NaN()일 수 없습니다:
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

하지만 [IShape::set_RawFrame](../../ishape/set_rawframe/) 메서드의 프레임은 정의되지 않을 수 있습니다. 이는 쉐이프가 플레이스홀더에 연결된 경우에 의미가 있습니다. 그런 경우 정의되지 않은 쉐이프 프레임 값은 부모 플레이스홀더 쉐이프에서 대체됩니다. 해당 쉐이프에 부모 플레이스홀더 쉐이프가 없으면 해당 쉐이프는 [IShape::get_RawFrame](../../ishape/get_rawframe/)를 기반으로 유효 프레임을 평가할 때 기본값을 사용합니다. 기본값은 x, y, width, height, flipH, flipV 및 rotationAngle에 대해 0과 [NullableBool::False](../../nullablebool/)입니다. 예시:
```cpp
SharedPtr<IShape> shape = ...; // shape은 플레이스홀더에 연결됩니다
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // 이제 shape은 플레이스홀더로부터 x, y, height, flipH, flipV 값을 상속받고 width=100 및 rotationAngle=0을 오버라이드합니다.
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShapeFrame](../../ishapeframe/)
* 클래스 [Shape](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)